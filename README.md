# Sistema de Recomendação de Conteúdo Individualizado e Predição de Risco de Evasão Escolar

## Descrição

Este projeto tem como objetivo analisar indicadores educacionais brasileiros para identificar padrões relacionados ao desempenho escolar e ao risco de evasão. Para isso, foram aplicadas técnicas de Ciência de Dados, Análise Exploratória de Dados (AED) e Machine Learning sobre dados públicos do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP).

O estudo busca demonstrar como a análise de dados pode auxiliar instituições de ensino na identificação de fatores associados ao abandono escolar e no desenvolvimento de estratégias de acompanhamento dos estudantes.

---

## Objetivo Geral

Desenvolver uma solução analítica capaz de identificar padrões associados à evasão escolar por meio da análise de indicadores educacionais e técnicas de Machine Learning.

---

## Objetivos Específicos

- Preparação e limpeza da base de dados;
- Realização da Análise Exploratória de Dados (AED);
- Identificação de padrões relacionados ao abandono escolar;
- Aplicação de um modelo de Machine Learning para classificação do risco de evasão;
- Interpretação dos resultados obtidos.

---

## Base de Dados

Foi utilizada a base pública **Taxas de Rendimento Escolar (2013–2023)**, disponibilizada pelo INEP e disponibilizada no Kaggle.

A base contém indicadores relacionados a:

- Aprovação escolar;
- Reprovação escolar;
- Abandono escolar;
- Região geográfica;
- Dependência administrativa;
- Unidade geográfica.

### Fonte dos Dados

https://www.kaggle.com/datasets/joaoassaoka/taxas-de-rendimento-escolar-inep

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Google Colab

---

## Estrutura do Projeto

```text
Projeto/
│
├── notebook.ipynb
├── taxas_rendimento.csv
├── README.md
└── imagens/
```

---

## Etapas do Desenvolvimento

### 1. Carregamento da Base de Dados

Importação das bibliotecas necessárias e carregamento do dataset.

### 2. Limpeza e Preparação dos Dados

- Tratamento de valores ausentes;
- Remoção de duplicidades;
- Correção de tipos de dados;
- Verificação de inconsistências.

### 3. Análise Exploratória de Dados (AED)

- Estatísticas descritivas;
- Identificação de padrões;
- Análise das variáveis educacionais.

### 4. Visualização dos Dados

- Gráficos de barras;
- Histogramas;
- Comparações entre indicadores educacionais.

### 5. Aplicação de Machine Learning

Utilização do algoritmo **Árvore de Decisão (Decision Tree)** para classificação do risco de evasão escolar.

**Variáveis preditoras:**
- Taxa_Aprovacao_Total_EM
- Taxa_Reprovacao_Total_EM

**Variável alvo:**
- Risco_Evasao

### 6. Discussão dos Resultados

Interpretação dos padrões encontrados e sua relação com o abandono escolar.

### 7. Conclusão

Apresentação das principais descobertas e possibilidades de trabalhos futuros.

---

## Resultados

O modelo de Árvore de Decisão apresentou uma acurácia de aproximadamente **92,70%**, indicando boa capacidade de identificar padrões associados ao risco de evasão escolar.

Os resultados demonstraram que indicadores de aprovação e reprovação possuem relação com as taxas de abandono, evidenciando o potencial da Ciência de Dados para apoiar a tomada de decisão no contexto educacional.

---

## Como Executar

### Clonar o Repositório

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
```

### Instalar Dependências

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Executar

Abra o notebook no Google Colab ou Jupyter Notebook e execute as células sequencialmente.

---

## Referências

- INEP — Taxas de Rendimento Escolar
- Kaggle — Taxas de Rendimento Escolar (2013–2023)
- Neri et al. (2009) — Motivos da Evasão Escolar
- Moraes e Kafure (2020) — Ciência de Dados
- Nascimento (2018) — Análise Exploratória de Dados
- Schleder e Fazzio (2021) — Machine Learning

---

## Autores

Projeto acadêmico desenvolvido para a disciplina de Big Data e Ciência de Dados, pelos acadêmicos Alec dos Santos, João Gabriel Massuda e Paulo Bruno Mendes.
