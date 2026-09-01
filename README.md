# Análise de Carga Elétrica - ONS (São Paulo, Agosto/2025)
 
Este repositório contém a resolução de um desafio de análise de dados utilizando a API pública do **Operador Nacional do Sistema Elétrico (ONS)**.
 
## Fonte dos dados
- **API:** [Carga Verificada - ONS](https://apicarga.ons.org.br/prd/cargaverificada)
- **Portal de dados:** [https://dados.ons.org.br/](https://dados.ons.org.br/)
- **Conjunto de dados:** [Carga/Energia Verificada](https://dados.ons.org.br/dataset/carga-energia-verificada)
 
## Período analisado
- **Área:** São Paulo (SP)
- **Data:** 01/08/2025 a 07/08/2025
 
## Estrutura do notebook
O notebook `analise_carga_ons.ipynb` contém:
 
- Consulta à API do ONS
- Criação e inspeção do DataFrame
- Organização e limpeza dos dados
- Cálculo de indicadores: mín, máx, média, mediana, amplitude
- Identificação de períodos de alta demanda (> 90% do pico)
- Segundo critério de análise (carga acima da média)
- Visualizações (série temporal e histograma)
- Síntese dos resultados para relatório
 
## Como executar
1. Abra o notebook no [Google Colab](https://colab.research.google.com/).
2. Execute todas as células (Runtime → Run all).
3. Os gráficos e tabelas serão exibidos ao final.

## Integrantes
- Vinicius Torralles, Rm: 570911
- Mariana Carminato, Rm: 573258
- Gabriel Jurado, Rm: 571236
 
## Integrantes
- [Nome do grupo]
