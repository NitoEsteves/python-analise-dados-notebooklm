# 📚 Caderno Temático: Python para Análise de Dados

> Projeto prático desenvolvido para o desafio da [DIO](https://www.dio.me/), utilizando o Google NotebookLM como ferramenta de aprendizagem ativa, curadoria de conhecimento e engenharia de prompts.

---

## 🎯 1. Contexto e Objetivos

* **Assunto de Interesse:** Python voltado para a Análise de Dados, com foco nas bibliotecas fundamentais (como o `Pandas`) e no fluxo de trabalho de um analista (coleta, limpeza, tratamento e visualização de dados).
* **Objetivos de Estudo:**
  1. Compreender o ecossistema de dados em Python e a importância da biblioteca Pandas.
  2. Aprender os comandos essenciais para manipulação de DataFrames (filtragem, agrupamento e tratamento de valores nulos).
  3. Estruturar um guia de referência rápida e reutilizável para futuras análises.

---

## 📂 2. Curadoria de Fontes

Para alimentar o NotebookLM e garantir a confiabilidade técnica, selecionei as seguintes fontes abertas e oficiais:

1. **Documentação Oficial do Pandas (Getting Started / User Guide)**
   * *Descrição:* Guia oficial introdutório da biblioteca Pandas, ideal para entender estruturas de dados fundamentais (Series e DataFrames).
   * *Link/Acesso:* [Pandas Documentation](https://pandas.pydata.org/docs/getting_started/index.html) (Arquivos exportados em PDF/Texto para o NotebookLM).
2. **Python for Data Analysis (Capítulos introdutórios abertos)**
   * *Descrição:* Conceitos fundamentais de manipulação de dados utilizando o ecossistema Python.
   * *Link/Acesso:* Repositórios e materiais educacionais abertos baseados no livro de Wes McKinney.
3. **Guia de Boas Práticas de Limpeza de Dados com Python**
   * *Descrição:* Artigo técnico abordando como lidar com dados ausentes, duplicados e inconsistências antes da análise.
   * *Link/Acesso:* Artigos abertos da comunidade em plataformas de tecnologia (ex: Real Python).

---

## 💡 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, testamos diferentes abordagens para extrair o melhor material de estudo:

* **Prompt Inicial (Teste 1):** *"O que é o Pandas?"*
  * *Resultado:* Resposta muito ampla e conceitual, focada apenas na história da biblioteca.
  * *Ajuste / Cicatriz:* Percebi que precisava pedir exemplos de código e direcionar para tarefas práticas de análise.
* **Prompt Refinado (Versão Final):** *"Aja como um cientista de dados sênior. Com base nas fontes carregadas, explique de forma prática como carregar um arquivo CSV, identificar valores nulos e usar o método groupby() no Pandas, incluindo blocos de código comentados para iniciantes."*
  * *Resultado:* Resposta rica, estruturada com explicações teóricas seguidas de exemplos de código claros e aplicáveis.

---

## 📝 4. Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados
* **O Ecossistema Python para Dados:** Python se destaca na análise de dados devido à sua sintaxe limpa e a um ecossistema robusto de bibliotecas especializadas. O **Pandas** é a ferramenta central para manipulação tabular, enquanto o **NumPy** atua nos cálculos numéricos de baixo nível e o **Matplotlib/Seaborn** cuidam da visualização gráfica.
* **Limpeza e Tratamento de Dados (Data Cleaning):** A maior parte do tempo de um analista (cerca de 80%) é gasta limpando dados. No Pandas, funções como `.isnull()`, `.fillna()`, `.dropna()` e `.drop_duplicates()` são essenciais para garantir a qualidade da base antes de gerar insights.
* **Agrupamento e Agregação:** O método `.groupby()` permite dividir os dados em grupos com base em critérios específicos, aplicar funções de agregação (como `.mean()`, `.sum()`, `.count()`) e extrair métricas consolidadas rapidamente.

### 📖 Glossário de Termos
* **DataFrame:** Estrutura de dados bidimensional, mutável em tamanho, com eixos rotulados (linhas e colunas), semelhante a uma tabela de banco de dados ou planilha do Excel.
* **Series:** Uma matriz unidimensional rotulada capaz de conter qualquer tipo de dados (inteiros, strings, ponto flutuante, etc.). Cada coluna de um DataFrame é essencialmente uma Series.
* **Valores Nulos (`NaN`):** Representam dados ausentes ou desconhecidos em um conjunto de dados, exigindo tratamento específico para não distorcer as análises estatísticas.
* **CSV (Comma-Separated Values):** Formato de arquivo de texto simples muito utilizado para armazenar dados tabulares, amplamente lido pelo Pandas através da função `pd.read_csv()`.

### 🔄 Prompts Reutilizáveis para Futuras Revisões
1. *"Com base nas fontes, crie um resumo em tópicos dos 5 principais métodos do Pandas para manipulação de colunas e linhas."*
2. *"Elabore um mini-exercício prático de código em Python usando Pandas para resolver um problema típico de vendas e faturamento."*
3. *"Explique a diferença entre os métodos de junção (merge e join) no Pandas de forma simples e com exemplos visuais em texto."*

---

## 🚀 Como Utilizar este Repositório
1. Acesse o [Google NotebookLM](https://notebooklm.google.com/).
2. Crie um novo caderno temático chamado **"Python para Análise de Dados"**.
3. Faça o upload das documentações e artigos citados na seção de Curadoria de Fontes.
4. Utilize os prompts da seção 3 e 4 para interagir com o seu material de estudo personalizado!
