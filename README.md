## 📡 Desafio Telecom X BR I — Análise de Churn

*ETL, Análise Exploratória de Dados e Business Insights com Python*

![Python](https://img.shields.io/badge/Python-Data%20Science-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Data Science](https://img.shields.io/badge/Data%20Science-EDA-success)
![Alura](https://img.shields.io/badge/Oracle%20ONE-Alura-0A3871)


### **Análise de Churn** é um projeto de Data Science desenvolvido para investigar os fatores associados à evasão de clientes de uma empresa de telecomunicações.

A solução utiliza **Python e análise exploratória de dados (EDA)** para extrair, transformar e analisar informações provenientes de uma API, identificando padrões relacionados ao comportamento dos clientes e gerando insights que podem apoiar estratégias de retenção.
O projeto foi desenvolvido durante a **Tech Foundation — Especialização Data Science**, integrante do programa **Oracle Next Education (ONE) G9 BR / Alura**.

---

## 🎯 Objetivo

Investigar os principais fatores associados ao **churn (evasão de clientes)** por meio de técnicas de preparação, transformação e análise de dados.
O estudo busca transformar dados brutos em informações que possam apoiar tanto decisões de negócio quanto etapas posteriores de modelagem preditiva.

---

## 💼 Problema do Negócio

A evasão de clientes representa um desafio relevante para empresas que operam com modelos de receita recorrente.
Compreender quais características estão associadas a uma maior probabilidade de cancelamento permite direcionar estratégias de :

- Retenção
- Fidelização
- Onboarding
- Precificação
- Cross-selling
- Gestão do relacionamento com clientes

O projeto utiliza análise de dados para identificar padrões que possam contribuir para essas decisões.

---

## 🔄 Pipeline de Dados

```text
API
 ↓
Extração dos Dados
 ↓
Tratamento e Padronização
 ↓
ETL
 ↓
Análise Exploratória
 ↓
Análise de Churn
 ↓
Correlação entre Variáveis
 ↓
Visualizações
 ↓
Insights
 ↓
Recomendações de Negócio

```

---

##🔬 Etapas do Projeto

1. Extração

Importação dos dados provenientes da fonte disponibilizada para o desafio.

2. Transformação

Preparação dos dados para análise, incluindo :

- Tratamento de inconsistências
- Padronização das informações
- Conversão de tipos
- Preparação das variáveis
- Criação de atributos necessários às análises

3. Análise Exploratória

Exploração estatística e visual das principais características da base.

4. Análise de Churn

Comparação do comportamento de clientes que permaneceram com aqueles que deixaram a empresa.

5. Correlação

Investigação das relações existentes entre diferentes características dos clientes e a evasão.

6. Business Insights

Transformação dos resultados analíticos em hipóteses e recomendações aplicáveis ao negócio.

---

## 📊 Principais Insights

📉 Churn da base

A análise identificou churn de aproximadamente 26% dos clientes, indicando também a necessidade de atenção ao desbalanceamento da variável-alvo em uma eventual etapa de Machine Learning.

📃 Tipo de contrato

Clientes com contratos Month-to-month apresentam maior incidência de churn quando comparados aos contratos de maior duração.

⏳ Tempo de relacionamento

Clientes com menor tenure concentram uma parcela relevante da evasão, indicando que os primeiros meses do relacionamento merecem atenção especial.

💰 Custo mensal

Foi observada uma tendência de maior churn entre clientes com valores mensais mais elevados, sugerindo possível sensibilidade a preço.

📦 Quantidade de serviços

Clientes que utilizam maior quantidade de serviços apresentam menor ocorrência de churn, indicando uma possível relação entre engajamento e retenção.

---

💡 Recomendações de Negócio

A partir dos padrões identificados, algumas estratégias podem ser investigadas:

Fortalecer ações de onboarding nos primeiros meses
Desenvolver estratégias de migração de contratos mensais para planos de maior duração
Avaliar a percepção de valor dos clientes com mensalidades mais elevadas
Incentivar a contratação de serviços complementares
Criar estratégias segmentadas de retenção para grupos com maior incidência de churn

Essas recomendações devem ser interpretadas como hipóteses orientadas pelos dados e validadas antes de sua implementação.

---

## 🛠️ Tecnologias Utilizadas

**Python** - Processamento e análise
**Pandas** - Manipulação e transformação dos dados
**NumPy** -	Operações numéricas
**Matplotlib**	- Visualização de dados
**Seaborn**	- Visualizações estatísticas
**Google Colab / Jupyter** -	Desenvolvimento e execução do notebook
**API / JSON** -	Fonte e estrutura dos dados

---

## 📂 Estrutura do Projeto

```text

Telecom-X-BR/
│
├── Telecom_X_BR.ipynb
└── README.md

```

---

## 💡 Competências Demonstradas

- Data Science
- Data Analytics
- ETL
- Exploratory Data Analysis (EDA)
- Python
- Pandas
- Data Cleaning
- Data Transformation
- Data Visualization
- Análise de correlação
- Customer Churn Analysis
- Business Analytics
- Data-Driven Decision Making

---

## 🚀 Próxima Etapa

A análise exploratória estabelece a base para uma evolução natural do projeto:

```text
EDA
 ↓
Feature Engineering
 ↓
Preparação dos Dados
 ↓
Machine Learning
 ↓
Predição de Churn
 ↓
Avaliação do Modelo
 ↓
Identificação de Clientes de Risco

```

Uma futura versão pode utilizar modelos de classificação para estimar a probabilidade de churn e apoiar estratégias preventivas de retenção.

---

## ➡️ Continuação:** Telecom X II — Predição de Churn com Machine Learning

---

👨‍💻 Autor

Marcus Guedes

Marketing | Data Science | Inteligência Artificial | Gestão de Projetos

GitHub: MCLG1661
LinkedIn: Marcus Guedes
