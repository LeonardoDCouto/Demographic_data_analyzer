# Projeto de Análise de Dados - FreeCodeCamp
 Este é um projeto proposto pelo curso de Análise de Dados com Python no FreeCodeCamp
 
 ## Proposta
 
Este projeto utiliza a biblioteca Pandas para analisar um conjunto de dados demográficos extraídos do banco de dados do Censo de 1994. Aqui estão algumas das perguntas que devem ser respondidas:

Quantas pessoas de cada raça estão representadas neste conjunto de dados?
Qual é a idade média dos homens?
Qual é a porcentagem de pessoas que têm um diploma de bacharel?
Que porcentagem de pessoas com educação avançada (Bacharelado, Mestrado ou Doutorado) ganha mais de 50 mil?
Que porcentagem de pessoas sem educação avançada ganha mais de 50 mil?
Qual é o número mínimo de horas que uma pessoa trabalha por semana?
Que porcentagem das pessoas que trabalham o número mínimo de horas por semana tem um salário superior a 50 mil?
Qual país tem a maior porcentagem de pessoas que ganham mais de 50 mil e qual é essa porcentagem?
Identifique a ocupação mais popular para quem ganha mais de 50 mil na Índia.

## Solução

A solução deste projeto foi implementada na função calculate_demographic_data(). Esta função realiza a leitura dos dados do arquivo 'adult.data.csv', realiza as análises necessárias e retorna um dicionário com os resultados obtidos.
As respostas para cada pergunta são calculadas e armazenadas em variáveis específicas. Por exemplo, o cálculo da idade média dos homens é feito filtrando as linhas onde o sexo é "Masculino" e calculando a média da coluna de idade. A porcentagem de pessoas com um diploma de bacharel é calculada contando o número de linhas onde o nível de educação é "Bacharelado" e dividindo pelo número total de linhas. Esses processos são feitos para todas as questões e os resultados são armazenados no dicionário final.
