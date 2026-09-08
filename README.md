# Exercícios Físicos BD (PT-BR)

Mais de **800 exercícios físicos** em português, organizados por categorias, músculos trabalhados e nível de dificuldade.

Este repositório é uma versão **traduzida** do projeto original [free-exercise-db](https://github.com/yuhonas/free-exercise-db).

---

## 📂 Estrutura do Dataset

O dataset está disponível em **3 versões**, de acordo com o nível de tradução:

---

### 1. `exercises-ptbr-minimal.json`

Tradução básica contendo apenas:

* `id`
* `name` (nome do exercício)
* `instructions` (passo a passo em português)

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "id": "3_4_Sit-Up"
}
```

---

### 2. `exercises-ptbr-partial-translation.json`

Tradução **parcial**:

* `name` e `instructions` em português
* Outras propriedades (como `category`, `level`, `primaryMuscles`, etc.) **em inglês**

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "force": "pull",
  "level": "beginner",
  "mechanic": "compound",
  "equipment": "body only",
  "primaryMuscles": [
    "abdominals"
  ],
  "secondaryMuscles": [],
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "category": "strength",
  "images": [
    "3_4_Sit-Up/0.jpg",
    "3_4_Sit-Up/1.jpg"
  ],
  "id": "3_4_Sit-Up"
}
```

---

### 3. `exercises-ptbr-full-translation.json`

Tradução **completa**, onde todas as propriedades foram adaptadas para o português:

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "force": "puxar",
  "level": "iniciante",
  "mechanic": "composto",
  "equipment": "peso-do-corpo",
  "primaryMuscles": [
    "abdominais"
  ],
  "secondaryMuscles": [],
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "category": "força",
  "images": [
    "3_4_Sit-Up/0.jpg",
    "3_4_Sit-Up/1.jpg"
  ],
  "id": "3_4_Sit-Up"
}
```

---

⚠️ Sobre as imagens

Os caminhos para imagens (images) foram mantidos no dataset para referência, mas as imagens originais não estão incluídas neste repositório.
Isso evita problemas de direitos autorais, já que não temos permissão para redistribuí-las.

---

## 🚀 Como usar

* Escolha o arquivo que melhor se adapta ao seu caso (mínimo, parcial ou completo).
* Faça o parse do JSON no seu projeto e utilize os dados conforme necessário.

---

## 📌 Créditos

* Tradução e adaptação: **Este repositório**
* Base original: [free-exercise-db](https://github.com/yuhonas/free-exercise-db)

---

## 📜 Licença

Este projeto está licenciado sob a [**CC0 1.0 Universal**](LICENSE) (dedicação ao domínio público).

Na prática, isso significa que **qualquer pessoa pode copiar, modificar, distribuir e utilizar este dataset**, inclusive em **projetos comerciais ou sem fins lucrativos**, sem pedir permissão e sem necessidade de atribuição.

A escolha da CC0 mantém a continuidade com o projeto original [free-exercise-db](https://github.com/yuhonas/free-exercise-db), que é publicado sob a [Unlicense](https://unlicense.org) — também uma dedicação ao domínio público.

> **Nota:** a licença cobre os arquivos JSON deste repositório (os dados e sua tradução). Ela **não** se aplica às imagens referenciadas no campo `images`, que não estão incluídas aqui e permanecem sob os direitos de seus respectivos autores.
