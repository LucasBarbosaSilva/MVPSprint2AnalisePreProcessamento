<h1 align="center"> MVP - Sprint 2 - Análise de Dados e Boas Práticas </h1>
<h2 align="center">Pós-Graduação em Ciência de Dados e Analytics pela PUC RJ</h2>
<h3 align="center">Análise do Dataset Bank Marketing (UCI Repository) </h3>

**Dataset:** [Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)

**Colab MVP:** [Notebook Colab do MVP](https://colab.research.google.com/github/LucasBarbosaSilva/MVPSprint2AnalisePreProcessamento/blob/main/MVP_Sprint_2_An%C3%A1lise_de_Dados_e_Boas_Pr%C3%A1ticas.ipynb)

## Descrição do Problema:
Consiste na análise e pré-processamento de um conjunto de dados sobre campanhas de marketing direto (chamadas telefônicas) de uma instituição bancária portuguesa. O objetivo da classificação é prever se o cliente irá se inscrever em um depósito a prazo (variável result).

## Hipóteses levantadas:
1. Clientes com resultado anterior 'sucesso' tendem a se inscrever novamente?
2. Clientes mais jovens (15 a 24 anos) tendem a se inscrever mais que clientes adultos (25 a 60 anos)?
3. Ligar mais vezes para um cliente diminui a chance dele contratar?
4. Dar mais dias de folga para o cliente, aumenta as chances de fechar contrato?

## Análise e resultados:
Embora o dataset esteja limpo, é extremamente desbalanceado, o que dificulta significativamente a análise do problema. Apesar do desbalanceamento, a análise exploratória revelou características importantes do problema, como maior taxa de aceitação entre clientes que já haviam assinado o produto, ou até mesmo uma quantidade de contatos mais adequada para maximizar a aceitação da campanha.

Embora, o desbalanceamento do dataset dificulte a análise mais clara dos resutlados, podemos afirmar que as quatro hipóteses levantadas foram validadas:

1. **Clientes com resultado anterior 'sucesso' tendem a se inscrever novamente?** <br>
*Sim, os clientes com sucesso na campanha anterior, foram os mais dispostos a aceitar novamente a campanha.*
2. **Clientes mais jovens (15 a 24 anos) tendem a se inscrever mais que clientes adultos (25 a 60 anos)?** <br>
*Sim, o público jovem teve maior taxa de aceitação do que o de adultos.*
3. **Ligar mais vezes para um cliente diminui a chance dele contratar?** <br>
*Podemos dizer sim, mas melhor seria dizer que não aumenta as chances.*
4. **Dar mais dias de folga para o cliente, aumenta as chances de fechar contrato?** <br>
*Depende, até 200 dias é considerado tempo saudável e que geralmente trás bom resultados. Após esse período, diminui significativamente os casos positivos.*

## Trabalhos Futuros
Seguir com a codificação do modelo de classificação.
