# Análise de Satisfação de Clientes e Modelagem Preditiva com Machine Learning em Dados NPS

Este projeto foi desenvolvido como parte de um trabalho acadêmico com o objetivo de realizar a análise exploratória, estatística e preditiva de dados de satisfação de clientes (NPS - Net Promoter Score) referentes ao "Grupo 1" de produtos em todo o território brasileiro, com base em dados históricos dos anos de 2022, 2023 e 2024.

## 🎯 Objetivos

- Realizar o pré-processamento de dados brutos de NPS.
- Classificar os clientes em **Promotores**, **Neutros** e **Detratores** com base em suas notas.
- Analisar a volumetria (quantidade e porcentagem) de cada categoria por safra (ano), região geográfica e período de pesquisa.
- Construir e avaliar modelos de Machine Learning para prever a propensão de um cliente ser detrator ou neutro.
- Identificar as variáveis mais relevantes por meio de gráficos de importância e Partial Dependence Plots (PDP).
- Calcular a correlação de Spearman das variáveis com a nota atribuída.

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Google Colab
- Excel (.xlsx)

## 🧪 Metodologia

O projeto segue as seguintes etapas:

1. **Importação e limpeza de dados:** conversão de datas, filtragem por grupo e mercado.
2. **Classificação NPS:** categorização dos clientes de acordo com a nota atribuída.
3. **Agrupamento por região e período:** divisão dos dados em regiões do Brasil e períodos de pesquisa (3 a 30 meses).
4. **Análise volumétrica:** geração de tabelas de contagem e porcentagem para cada categoria por ano, região e período.
5. **Modelagem preditiva:**
   - Treinamento de dois modelos com RandomForest: um para prever detratores e outro para neutros.
   - Avaliação com métricas como acurácia, precisão, recall, F1-score, curva ROC e matriz de confusão.
6. **Análise de importância de variáveis e PDPs:** identificação dos principais fatores influenciadores para cada modelo.
7. **Correlação de Spearman:** análise das correlações estatísticas com a nota atribuída pelos clientes.

## 📊 Resultados Esperados

- Identificação dos principais fatores que influenciam a insatisfação e neutralidade de clientes.
- Insights segmentados por ano, região e tempo de uso do produto.
- Ferramentas de apoio à tomada de decisão para melhorar a experiência do cliente.

## 📂 Estrutura do Código

O código está organizado em seções:

- Funções auxiliares: visualizações, correlações e criação de modelos.
- Etapas de análise: separadas por safra, região e período.
- Criação e avaliação de modelos: métricas, gráficos e importância de variáveis.

## 📌 Requisitos

- Python 3.8+
- Pacotes: pandas, numpy, scikit-learn, seaborn, matplotlib, openpyxl

## 🚀 Como Executar

1. Faça upload do arquivo de dados `Lista NPS Positivo_V4 (1).xlsx` no ambiente.
2. Execute o script `cnhgrupo1.py` (pode ser rodado em um notebook Colab).
3. Acompanhe os resultados das análises e avaliações dos modelos no output.

## 👨‍🏫 Autoria

Projeto desenvolvido por alunos como parte da disciplina de [nome da disciplina], [nome da instituição].

