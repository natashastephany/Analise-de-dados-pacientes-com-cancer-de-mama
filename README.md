# Análise de dados de câncer de mama

## Objetivo do projeto

O intuito do projeto foi explorar os dados de pacientes com câncer de mama, de modo a extrair informações. Para isto, foram elaboradas 4 perguntas norteadoras:

1) Há uma sugestão de relação entre os níveis de expressão de proteínas, a idade e o status do paciente?
2) Há uma sugestão de relação entre o estágio do câncer e a situação do paciente?
3) Há uma sugestão de relação entre o tipo de cirurgia e a situação do paciente?
4) Há uma sugestão de relação entre a idade do paciente e a situação do paciente?

## Fonte de dados 

Os dados foram extraídos da Base de Dados Kaggle (disponível no link: https://www.kaggle.com/datasets/kellistephenson/increasing-breast-cancer-awareness?resource=download), que por sua vez foram extraídos do site BioGPS (http://biogps.org/dataset/tag/brca1/). O conjunto de dados escolhido possui o título de "Increasing Breast Cancer Awareness" (Aumentando a conscientização sobre o câncer de mama), e trata-se de dados de pacientes com câncer de mama. O dataset possui 334 linhas e 15 colunas, cuja variáveis encontram-se descritas no dicionário de dados abaixo.

#### Dicionário de dados

Age - idade do paciente;
Gender - gênero do paciente;
Protein1, Protein2, Protein3, Protein4 - níveis de expressão de 4 tipos de proteína diferentes;
Tumour_Stage - estágio do tumor (1, 2 ou 3)
Histology - histologia ()
ER status -
PR status -
HER2 status -
Surgery_type - tipo de cirurgia ()
Date_of_Surgery - data da cirurgia
Date_of_Last_Visit - data da última visita ao paciente
Patient_Status - status do paciente (vivo ou morto)

## Etapas do projeto

Este projeto foi dividido em quatro etapas:

1) Exploração inicial dos dados - nesta etapa foi feita uma breve exploração dos dados, apenas para visualizar como os dados estavam apresentados na tabela.
2) Limpeza e tratamento dos dados - nesta etapa os dados ausentes/nulos foram tratados.
3) Análise exploratória - esta etapa avaliou a necessidade de alteração das variáveis. Algumas delas foram excluídas.
4) Análise dos dados - esta etapa final se destinou a responder as perguntas feitas no início do projeto. Para isto, alguns gráficos foram gerados.
   
Este projeto foi inteiramente realizado utilizando-se a linguagem Python, com o interpretador Jupyter Notebook. Todas as etapas estão descritas no arquivo do Jupyter Notebook "Projeto1".
