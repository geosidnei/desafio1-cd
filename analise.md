
Módulo 3 - Análise Exploratória

Iniciamos importando as bibliotecas necessárias e lendo o arquivoAdventureWorks.xlsx:


![1_upload_data](https://github.com/geosidnei/desafio1-cd/blob/main/1_upload_data.png)

Tratamento inicial dos dados:

Criamos as novas colunas Custo Unitário, Quantidade e Lucro:

![2_novas%20colunas](https://github.com/geosidnei/desafio1-cd/blob/main/2_novas%20colunas.png)

Descobrimos os totais de venda, custo e lucro:

![3-totais_venda_custo_lucro](https://github.com/geosidnei/desafio1-cd/blob/main/3-totais_venda_custo_lucro.png)

Criação de nova coluna: Tempo de envio:

![4_coluna_tempo_de_envio](https://github.com/geosidnei/desafio1-cd/blob/main/4_coluna_tempo_de_envio.png)

Para calcular a média do tempo de envio foi necessário converter o campo Tempo em formato numérico extraindo a palavra days:

![5-converte_Tempo_envio_numero](https://github.com/geosidnei/desafio1-cd/blob/main/5-converte_Tempo_envio_numero.png)

Operações para saber a média do tempo de envio por marca e se há colunas com valores nulos:


![6-m%C3%A9dias](https://github.com/geosidnei/desafio1-cd/blob/main/6-m%C3%A9dias.png)


Passando os números para formato amigável aos humanos (em minha IDE tive que colocar outros parâmetros dentro das chaves, mas deu certo:


![7-n%C3%BAmeros-humano-amigaveis](https://github.com/geosidnei/desafio1-cd/blob/main/7-n%C3%BAmeros-humano-amigaveis.png)

Total de vendas para cada produto do estoque:


![8-total-vendas](https://github.com/geosidnei/desafio1-cd/blob/main/8-total-vendas.png)


E na forma de gráfico de barras:

![9-Gr%C3%A1fico_Total_de_Vendas](https://github.com/geosidnei/desafio1-cd/blob/main/9-Gr%C3%A1fico_Total_de_Vendas.png)


O gráfico do lucro por ano:


![10-Gr%C3%A1fico_Lucro-por-Ano](https://github.com/geosidnei/desafio1-cd/blob/main/10-Gr%C3%A1fico_Lucro-por-Ano.png)

Mas, como os números no gráfico estavam em formato científico, foi necessário convertê-los para um formato mais amigável aos humanos:

![11-numeros-amigaveis-Lucro%20por%20Ano](https://github.com/geosidnei/desafio1-cd/blob/main/11-numeros-amigaveis-Lucro%20por%20Ano.png)

