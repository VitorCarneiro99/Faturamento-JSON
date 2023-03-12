# Faturamento-JSON
Este programa lê um arquivo JSON com informações sobre faturamento diário de uma empresa e realiza algumas operações para analisar os dados. Primeiro, ele usa a biblioteca JSON para carregar os dados do arquivo 'dados.json' em uma lista de dicionários chamada "dados_json".

Em seguida, ele percorre essa lista de dicionários e armazena o menor e o maior valor de faturamento, juntamente com o dia em que ocorreram. Ele também calcula o faturamento total e a média do mês.

Depois, ele percorre novamente a lista e conta quantos dias tiveram um faturamento acima da média. Logo após, ele imprime na tela as seguintes informações: menor valor de faturamento e dia correspondente, maior valor de faturamento e dia correspondente, número de dias com faturamento acima da média e faturamento total do mês.

O programa usa alguns recursos básicos de manipulação de arquivos, iteração sobre listas e cálculo de média e acumuladores para realizar a análise de dados.
