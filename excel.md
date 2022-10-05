
Módulo 2 - Trabalhando com Planilhas do Excel

Em primeiro lugar foi necessário importar os módulos pandas e openpyxl para poder abrir or arquivos. Depois abrimos os 5 arquivos excel, como mostra a figura 1:

![exc1_uploading_data](https://github.com/geosidnei/desafio1-cd/blob/main/exc1_uploading_data.png)


Depois, juntamos todos arquivos com concat, verificamos com head, shape e dtypes para, então, trocar o tipo do objeto da coluna LojaID de int para object:

![exc2_organiz_dados](https://github.com/geosidnei/desafio1-cd/blob/main/exc2_organiz_dados.png)


A seguir, continua a preparação dos dados, com a verificação da existência de valores nulos com isnull, a criação da coluna de Receita, a verificação se ela realmente foi criada e a extração de algumas informações: maior e menor receita e as lojas que mais tiveram Receita:


![exc3_working](https://github.com/geosidnei/desafio1-cd/blob/main/exc3_working.png)



O trabalho continua com as menores receitas, as vendas totais por cidade e a ordenação do saldo de vendas:


![exc4_working2](https://github.com/geosidnei/desafio1-cd/blob/main/exc4_working2.png)


Como os dados que abri já estavamo no formato correto, a seguir agrupamos as vendas por ano e somamos as receitas totais de cada ano:


![exc5_working3](https://github.com/geosidnei/desafio1-cd/blob/main/exc5_working3.png)


Extraindo dados, como mês e dia da venda e outros processamentos derivados dessa extração:

![exc6_working4](https://github.com/geosidnei/desafio1-cd/blob/main/exc6_working4.png)


E outros processantos, bem como a triação da coluna Trimestre_venda:


![exc7_working5](https://github.com/geosidnei/desafio1-cd/blob/main/exc7_working5.png)

Criação da coluna vendas de março de 2019:

![exc8_vendas_marco_2019](https://github.com/geosidnei/desafio1-cd/blob/main/exc8_vendas_marco_2019.png)

Contagem dos valores por loja:

![exc9_value_counts](https://github.com/geosidnei/desafio1-cd/blob/main/exc9_value_counts.png)


E um gráfico de colunas relacionado às vendas totais por cidade da região nordeste onde a rede tem unidades de suas lojas:


![exc10_grafico_vendas_por_cidade](https://github.com/geosidnei/desafio1-cd/blob/main/exc10_grafico_vendas_por_cidade.png)
