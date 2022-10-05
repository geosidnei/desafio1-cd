
Módulo 1 - Trabalhando com o arquivo do tipo csv

Preferi trabalhar offline, então instalei o ambiente Anaconda e fiz todo o trabalho usando sua IDE SPYDER (Scientific PYthon Development EnviRonment) na versão 5.1.5, mostrada na figura abaixo:

![cd1.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd1.png)

Para abrir o arquivo localmente precisei apenas informar seu caminho correto. 
O comando df.head() funcionou:

![cd2.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd2.png)

Seguindo os passos da Profa Fernanda, a próxima etapa foi renomear as colunas, como mostrado abaixo:

![cd3_renomeando_colunas.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd3_renomeando_colunas.png)

Em seguida, o comando df.shape indica as linhas e colunas da base de dados:

![cd4_shape_tamanho_planilha.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd4_shape_tamanho_planilha.png)

O comando dtypes informa os tipos de dados da base:

![cd5_dtypes_tipos_de_dados.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd5_dtypes_tipos_de_dados.png)

No SPYDER tem que abrir uma janela extra para ver todas as colunas da planilha:
![cd6a_tail_expec_vida.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd6a_tail_expec_vida.png)

Mas, como professor de geografia, não poderia deixar de comentar estes  dados da parte final da planilha: vejam na imagem acima e na imagem abaixo baixas expectativas de vida e PIB per capita na África!

![cd6_tail.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd6_tail.png)

O comando describe traz um resumo estatístico da base de dados:

![cd7_describe_estats.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd7_describe_estats.png)

Para criar um subconjunto de dados usa-se o comando loc com as combinações certas de colunas:

![cd8_subconjuntoOceania.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd8_subconjuntoOceania.png)

Fato confirmado na janela abaixo:

![cd8a_74l_6c.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd8a_74l_6c.png)

O resumo estatístico (comando describe) do subconjunto Oceania:

![cd9_describe_Oceania.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd9_describe_Oceania.png)

Uma contagem fica fácil com a integração do agrupamento por colunas e o comando nunique:

![cd10_groupby.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd10_groupby.png)

A média da expectativa de vida para cada ano requer um agrupamento dos anos, das expectativas de vida e o cálculo da média de cada ano:
(1950 a 1952)...

![cd11_expecv1.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd11_expecv1.png)

E o recorte mostra o final dos dados  (2003 a 2007):

![cd11_expecv2.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd11_expecv2.png)

O código seguinte

"import matplotlib.pyplot as plt
df.groupby("Ano")["Expectativa_Vida"].mean().plot.bar(title="Mundo: Expectativa de Vida [1950 - 2007]"

resultou no gráfico rudimentar abaixo:

![cd11_expecv3.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd11_expecv3.png)

Procedemos à criação de outro subconjunto de dados, agora para a América (faltaram alguns países, não tem Canadá, Haiti e outros...):

![cd12_America.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd12_America.png)

E o gráfico dos países da América escolhidos para esta base de dados, para completar este ótimo primeiro exercício que a professora Fernanda nos passou:

![cd12_AmericaGrafico.png](https://github.com/geosidnei/desafio1-cd/blob/main/cd12_AmericaGrafico.png)


Home: -------------------------------> https://github.com/geosidnei/desafio1-cd/blob/main/README.md

Módulo 2: Excel: --------------------> [https://github.com/geosidnei/desafio1-cd/blob/main/excel.md]

Módulo 3: Análise exploratória: -----> [https://github.com/geosidnei/desafio1-cd/blob/main/analise.md]
