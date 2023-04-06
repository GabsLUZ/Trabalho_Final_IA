# Trabalho_Final_IA

- I. Definição de Dados
- II. [Preparação de Dados](https://github.com/GabsLUZ/Trabalho_Final_IA/blob/main/trabalho_final_I_A_Dados.ipynb)
- III. [Teste e Avaliação](https://github.com/GabsLUZ/Trabalho_Final_IA/blob/main/Teste_Avaliza%C3%A7%C3%A3o.ipynb)
- IV. [Melhora dos Resultaods](https://github.com/GabsLUZ/Trabalho_Final_IA/blob/main/Melhorando_Resultados.ipynb)



# Modelo preditivo para prognóstico de pacientes com COVID-19


Durante a pandemia de coronavirus disease 2019 (COVID-19) os sistemas de saúde do mundo inteiro enfrentam problemas quanto a disponibilidade e alocação de recursos como respiradores e leitos de UTI (Unidade de Terapia Intensiva). Políticas e decisões críticas estão sendo tomadas quanto a priorização de pacientes com a doença e, em países como o Brasil, existem regras que definem quem tem direito a leitos de UTI. Em alguns lugares, devido a urgência e falta de dados mais precisos, a política tem sido priorizar as pessoas mais jovens para a ocupação dos leitos de UTI. Em estados como o Rio Grande do Sul, não há leitos para todos os pacientes em estado grave, consequentemente, é preciso colocar em prática políticas de priorização da alocação dos leitos com base no estado clínico do paciente.

Estudos mostram que modelos de aprendizagem de máquina (machine learning) conseguem predizer a chance de óbito de um paciente positivo para COVID-19 com até 0,99 de pontuação AUC-ROC (Area Under the Curve - Receiver Operating Charachteristic Curve). Por se tratar de um contexto crítico (pandemia erisco de vida), os modelos preditivos devem ser robustos, seguros e transparentes, semc omprometer a ética. Um dos principais desafios é desenvolver e garantir a credibilidade desses modelos.

Neste trabalho, propomos um modelo preditivo baseado em florestas aleatórias para classificação de risco de óbito para pacientes confirmados de COVID-19 no estado do Rio Grande do Sul/Brasil. Utilizamos a pontuação AUC-ROC para avaliar a performance do modelo. Este é um indicador importante pois nos fornece uma medida da precisão total do modelo independente de um limiar particular. O desenvolvimento do modelo é explanado utilizando o guia TRIPOD para atenuar o risco da falta de detalhes. Utilizamos também da validação cruzada 5-fold para validar internamente o modelo e, desta forma, reduzir o risco de enviesamento.
