# Análise de Custos Médicos e Impacto do Tabagismo.


##  O Problema de Negócio
Em empresas de saúde e planos de convênio, entender o que encarece o serviço é fundamental para a precificação e criação de campanhas de prevenção. O objetivo deste projeto foi analisar uma base de dados de pacientes para descobrir: **qual é o impacto financeiro do tabagismo nos custos médicos?**

##  Ferramentas e Tecnologias
* **Linguagem:** Python
* **Bibliotecas:** Pandas (ETL) e Seaborn/Matplotlib (Visualização)
* **Ambiente:** Google Colab

##  O que foi feito (Pipeline)
1. **Extração:** Coleta de dados brutos de custos médicos.
2. **Transformação:** 
   * Tradução de colunas e dados para o Português.
   * Conversão da moeda para Reais (R$).
3. **Visualização:** Criação de um Boxplot minimalista com foco em leitura executiva.

##  Principais Insights
Através da análise visual, ficou evidente que **pacientes fumantes geram um custo médico significativamente maior** para o plano de saúde, com a média de gastos em um patamar muito superior ao dos não fumantes. Além disso, identificamos *outliers* (casos isolados de alto custo) entre os não fumantes, possivelmente atrelados a acidentes ou doenças graves inesperadas.
