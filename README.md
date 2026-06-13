# Caderno Temático: Fundamentos de Python para Análise de Dados e BI

## 🎯 Contexto e Objetivos
Este repositório contém um miniguia de estudos gerado com o apoio do NotebookLM, focado na aplicação prática do Python para manipulação de dados.
**Objetivo:** Dominar a biblioteca Pandas para automatizar a limpeza de planilhas, estruturar dados financeiros e prepará-los para a criação de dashboards de Business Intelligence.

## 📚 Curadoria de Fontes
1. [Documentação Oficial do Pandas] - Guia de manipulação de DataFrames.
2. [Artigo/Capítulo de Livro sobre ETL] - Conceitos de Extração, Transformação e Carga.
3. [Base de dados pública do Kaggle] - Dataset de vendas de varejo utilizado para os testes práticos.

## 🛠️ Engenharia de Prompts e "Cicatrizes"

### Tentativa 1 (O erro do escopo amplo)
* **Prompt:** "Me ensine a usar Pandas para análise de dados."
* **Resultado:** A IA gerou um tutorial imenso e teórico que não me ajudou a resolver problemas reais.
* **Troubleshooting (Ajuste):** Percebi que precisava dar um cenário de negócios para a IA.

### Tentativa 2 (Foco em resolução de problemas)
* **Prompt:** "Atue como um Analista de BI Sênior. Tenho uma planilha de vendas com datas em formatos errados e valores nulos. Usando a biblioteca Pandas do Python, qual é o passo a passo e o código mais eficiente para limpar e padronizar essa base?"
* **Resultado:** A IA forneceu funções específicas (`dropna()`, `to_datetime()`) com explicações claras do impacto de cada uma no negócio.

## 📓 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado: O Ciclo de Limpeza de Dados com Python
1. **Importação:** Leitura de arquivos `.csv` e `.xlsx` usando `pd.read_csv()`.
2. **Inspeção Inicial:** Uso de `df.head()` e `df.info()` para entender o volume de dados e os tipos de variáveis.
3. **Tratamento de Nulos:** Estratégias de preenchimento ou exclusão de dados faltantes para não distorcer o ROI no BI.
*(Continue com o resumo que a IA gerar para você)*

### Glossário
* **DataFrame:** A estrutura de dados bidimensional (como uma tabela de Excel) usada pelo Pandas.
* **ETL (Extract, Transform, Load):** Processo de extrair dados de uma fonte, limpá-los/transformá-los e carregá-los no destino final (dashboard ou banco de dados).
