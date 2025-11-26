# Análise de Dados: Fatores de Risco Comportamentais e Incidência de Câncer em SP

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Concluído-green)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC) em Ciência de Dados. O objetivo foi investigar a correlação entre fatores de risco comportamentais (tabagismo, alimentação, sedentarismo) e a incidência de câncer no estado de São Paulo.

O diferencial técnico deste projeto reside na integração e tratamento de dados públicos heterogêneos (ETL), transformando bases brutas governamentais em insights acionáveis de saúde pública.

## 💼 Contexto e Problema
A incidência de câncer é multifatorial, mas o estilo de vida desempenha um papel crucial. O desafio consistia em:
1. Unificar dados de comportamento populacional (Vigitel).
2. Cruzar com dados de registros hospitalares de câncer (INCA).
3. Identificar padrões estatísticos relevantes na população de São Paulo.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Fontes de Dados:** * **Vigitel:** Vigilância de Fatores de Risco e Proteção para Doenças Crônicas.
    * **RHC/INCA:** Registro Hospitalar de Câncer.

## 📊 Pipeline de Dados (Metodologia)
O projeto seguiu um fluxo estruturado de Ciência de Dados:

1.  **Coleta de Dados:** Extração de microdados públicos.
2.  **Limpeza e Pré-processamento (Data Cleaning):**
    * Tratamento de valores nulos e *outliers*.
    * Normalização de nomes de variáveis entre as bases.
    * Filtragem geográfica (foco no Estado de SP).
3.  **Engenharia de Atributos:** Criação de categorias para faixas etárias e grupos de risco.
4.  **Análise Exploratória (EDA):** Visualização de distribuições e correlações.

## 🚀 Como Executar este Projeto
Pré-requisitos: Python instalado e bibliotecas listadas no `requirements.txt`.

```bash
# Clone este repositório
git clone [https://github.com/seu-usuario/nome-do-repo.git](https://github.com/seu-usuario/nome-do-repo.git)

# Instale as dependências
pip install -r requirements.txt

# Execute o Jupyter Notebook
jupyter notebook analise_cancer_sp.ipynb
