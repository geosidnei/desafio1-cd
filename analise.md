
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

Criação da tabela de vendas apenas para o ano 2009:


![12-vendas%20de%202009](https://github.com/geosidnei/desafio1-cd/blob/main/12-vendas%20de%202009.png)


Gráfico de linhas já com as letras da legenda do eixo x na horizontal:


![13-grafico-linha-lucro-por-mes](https://github.com/geosidnei/desafio1-cd/blob/main/13-grafico-linha-lucro-por-mes)


Gráfico de colunas com o lucro por marca, mas esqueci de transformar os números em amigáveis aos humanos...


![14-Lucro%20por%20Marca](https://github.com/geosidnei/desafio1-cd/blob/main/14-Lucro%20por%20Marca)


Gráfico de colunas com o lucro por classe de produto:


![15-grafico-lucro%20por%20classe](https://github.com/geosidnei/desafio1-cd/blob/main/https://github.com/geosidnei/desafio1-cd/blob/main/15-grafico-lucro%20por%20classe.png)


Uma estatística da coluna Tempo de Envio...

![16-describe](https://github.com/geosidnei/desafio1-cd/blob/main/16-describe.png)


E o gráfico de box plot, que representa os dados constantes acima, no qual a bolinha no 20 é o valor discrepante superior, a caixa contém os três primeiros quartis e o valor mínimo é a base, no caso o valor 4:


![17-grafico-box-plot-tempo-envio](https://github.com/geosidnei/desafio1-cd/blob/main/17-grafico-box-plot-tempo-envio.png)


E é isso!

Nâo tenho palavras para agradecer à DIO pela oportunidade de fazer uma digna transição de carreira!
Professora Fernanda, muito obrigado, de coração!


Módulos deste curso:

1. CSV: [https://github.com/geosidnei/desafio1-cd/blob/main/csv.md]

2. Excel: [https://github.com/geosidnei/desafio1-cd/blob/main/excel.md]

Início: [https://github.com/geosidnei/desafio1-cd/edit/main/README.md]
   

