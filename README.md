# 📊 Análise de Salários em Dados

Projeto desenvolvido durante a **Imersão Dados com Python** da Alura, com foco em exploração, limpeza e visualização de dados salariais da área de tecnologia/dados ao redor do mundo.

---

## 🎯 Objetivo

Analisar um dataset real de salários da área de dados para extrair insights sobre:
- Distribuição salarial por nível de senioridade
- Proporção de tipos de trabalho (Remoto, Híbrido, Presencial)
- Salário médio de Data Scientists por país
- Comportamento e distribuição global dos dados salariais

---

## 🗂️ Dataset

- **Fonte:** [`salaries.csv`](https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv)
- **Conteúdo:** Registros de profissionais da área de dados com informações de cargo, senioridade, tipo de emprego, salário em USD, país de residência e porte da empresa
- **Colunas principais:** `cargo`, `senioridade`, `tipoEmprego`, `salario_usd`, `txRemoto`, `paisEmpresa`, `porte`

---

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📋 Etapas do Projeto

### 1. 🔍 Exploração dos Dados
- Carregamento do dataset via URL com Pandas
- Análise inicial com `.head()`, `.info()`, `.describe()` e `.shape`
- Identificação e mapeamento das colunas para português
- Substituição de valores codificados por descrições legíveis (ex: `MI` → `Pleno`, `SE` → `Sênior`)

### 2. 🧹 Preparação e Limpeza
- Verificação e tratamento de valores nulos com `.isnull()`
- Estratégias de preenchimento: média, mediana, `ffill`, `bfill` e valor padrão
- Remoção de linhas com valores nulos via `.dropna()`
- Correção de tipos de dados (conversão da coluna `ano` para `int64`)

### 3. 📈 Visualização e Gráficos
- **Matplotlib + Seaborn:** Gráfico de barras de senioridade, histograma da distribuição salarial e boxplots
- **Plotly Express:** Gráfico de barras interativo de salário médio por senioridade, gráfico de pizza/donut com proporção de tipos de trabalho, gráfico de barras por país para Data Scientists e **mapa coroplético interativo** com salário médio por país
---

## 🚀 Como executar

## 🚀 Como executar

1. Acesse o [Google Colab](https://colab.research.google.com)
2. Faça upload do arquivo `analise_salarios_dados.ipynb`
3. Execute as células em ordem sequencial
4. Todas as dependências já estão disponíveis no Colab, exceto `pycountry` — instalada via `pip` dentro do próprio notebook

---

## 📚 Contexto

Projeto desenvolvido na **Imersão Dados com Python** da Alura — evento gratuito focado em análise de dados com Python, cobrindo desde exploração até visualizações interativas com Plotly.

---

## 👨‍💻 Autor

**Iago Matheus**  
Estudante de Engenharia de Software — UNISA  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/iagomatheus)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IagoMat)
