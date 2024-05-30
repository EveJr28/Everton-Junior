# Analise da Dados - Itau

Meu projeto contém um código que realiza análise dos dados do arquivo proposto Ecommerce_DBS.CSV. As analises dados pelos códigos incluem visualização e modelagem de dados, analises estáticas e a visualização em gráficos das questões impostas pelo recrutador
As analises a seguir foram feitas pelo Itau_test.ipynb, onde utilizei o programa visual Studio Code, bibliotecas que foram usadas Pandas e Matplotlib para gerar gráficos e dados estatísticos 
Utilize o texto para colunas delimitado e algumas formulas como cont.se e somase além de filtro no excel para validar os dados também filtrei as faixas etarias entre 15 e 80 anos.

## Requisitos

- Python 3.x
- Pandas
- Matplotlib

## Como Usar

1. Clone o repositório ou baixe o código
2. Certifique-se de usar algum editor de código-fonte para Python 3
3. Baixe as bibliotecas acimas mencionadas

## Explicação 
Foram utilizados os seguintes roteiros de analise:
1.	Quais produtos mais vendidos considerando os últimos 3 anos?
2.	Qual o produto mais caro e o mais barato?
3.	Qual a categoria de produto mais vendido e menos vendida? Qual a categoria mais e menos cara?
4.	Qual o produto com o melhor e pior NPS?

Quais produtos mais vendidos considerando os últimos 3 anos?
Os produtos mais vendidos nos últimos 3 anos foram Books (livros), com 415277 unidades, Logo em seguida temos Clothing (Roupas) com 420069 vendas; Eletronics (produtos eletrônicos), com 278316 vendas e Home (produtos de casa), com 275745 vendas.

![vendas_ultimos_3_anos](https://github.com/EveJr28/img/assets/168125942/91d921d4-5de1-48e5-9c2e-177a800cc5c3)

Qual o produto mais caro e o mais barato?
Todas as categorias possuem produtos com um valor mínimo de 10R$ e valor máximo de 500R$.

![produtomaiseoumaisbarato](https://github.com/EveJr28/img/assets/168125942/b3b6f758-1c4b-4e09-9a51-40a0b8a730d3)

Qual a categoria de produto mais vendido e menos vendida? Qual a categoria mais e menos cara?
A Categoria de produtos mais vendido foram Books(livros) com um total de 223876 unidades vendidas, seguida Clothing(roupas) com 225322 unidades vendidas, em terceiro e quarto lugar respectivamente seguem Electronics(eletrônicos) com 150828 unidades vendidas e Home(produtos de casa) com 149698 unidades vendidas. 

![QTD of Product for Category](https://github.com/EveJr28/img/assets/168125942/5bbf263b-9607-4481-a4bf-a7f3abda4a0a)

Todas as categorias tem o menor preço em 10 $ e o maior em 500$ porém a classificação média de preços por unidade é o seguinte rank: Home média de 254,84$, Eletronics, 257,72$, Books com 257, 71$ e Clothings com 257,45$

![Media preco do produto por cateogira](https://github.com/EveJr28/img/assets/168125942/a832a55c-807a-49d1-be9a-b028ec58bf5e)

Qual o produto com o melhor e pior NPS?
As quatro categorias possuem produtos com o NPS máx (10) e mín (0). 

![Maior e menor NPS por categoria](https://github.com/EveJr28/img/assets/168125942/2899ae26-dd1c-473c-8915-713c29514558)

A categoria que tem o melhor NPS médio é a Home, (produtos para casa), com 5.01 de média, e a pior é a Eletronics (produtos eletrônicos), com 4.97 de média.

![MEdia NPs por categoria](https://github.com/EveJr28/img/assets/168125942/a7b2067b-d843-46e5-aaa5-21d060a8aa92)

## Análises
- Eletronics: 

Nos produtos eletrônicos os clientes mais acessaram aos nossos produtos segundo o data set foi através do "Instagram Campaign" com aproximadamente 28%. O Produto "FaceBook Campaign" e o “SEM” tiveram desempenho semelhante, aproximadamente 26% das vendas. Já a busca orgânica teve um desempenho inferior, sendo responsável por aproximadamente 19% das vendas. Sendo “Instragram Campaign” o modelo com mais retornos.Sendo o canal ideal “Instagram Campaing”

![Venda de eletronicos por canal](https://github.com/EveJr28/img/assets/168125942/3c4cf37c-7307-4d92-b87b-9cb3f86770f5)

Os maiores compradores estão entre as mulheres com pouca diferença sendo 50.07% para mulheres e 49.93% para homens. 

![percentage de vendas eletronicos por genero](https://github.com/EveJr28/img/assets/168125942/6285aa6e-5a93-4132-a53f-e0d602efbe10)

Enquanto a faixa etária entre 20 e 24 destoa com 10.33% das vendas totais durante o período analisado e a faixa etária entre 70 e 74 com a menor range de compra representando 2.10% abaixo com mais detalhes:

![qtd venda eletronicos por faixa etaria](https://github.com/EveJr28/img/assets/168125942/541305d7-c6e5-42d7-a7d3-7be732e7cf3c)

A média de NPS ficou com média 4,99 para homens e 4,95 para mulheres.

![media de NPS eletronico por genero](https://github.com/EveJr28/img/assets/168125942/a7f03110-0715-4357-b451-9d88aa8f1772)

- Books:

Para livros(books), a melhor estratégia apresentada de alcance foi “Instagram Campaing” com 27,95% dos acessos, seguidos de “Facebook Campaing” com 27%, “SEM“ e “Organic Search” seguidos de respectivamente de 26.63% e 18.42%. Sendo o canal ideal “Instagram Campaing”.

![venda de livros por canal](https://github.com/EveJr28/img/assets/168125942/fab326cd-d266-4b41-bf5d-c434487b63f6)

Entre os livros os maiores compradores estão entre 20 e 24 anos representando 10% das compras totais, enquanto a menor faixa de idade é entre 70 e 74 anos representando 1.96%

![faixa etaria de livros](https://github.com/EveJr28/img/assets/168125942/ef7b7608-abbf-48f1-8928-7f320c170ff7)

Enquanto a comparação entre os gêneros ficou com 50.02% para as mulheres e 49.98% para homens

![percentage de venda livros por genero](https://github.com/EveJr28/img/assets/168125942/1ba4a752-5b37-45d4-9d2e-4d7a120acd75)

Enquanto o NPS destrinchada ficamos com media 5 para o gênero feminino e 5.01 para o masculino

![media nps livros por genero](https://github.com/EveJr28/img/assets/168125942/b2578f0f-f964-4783-916d-270a33b84c5e)

- Home:

Nos produtos para casa (Home), a melhor estratégia segue com “instagram Campaing” com 28,27% e “Facebook Campaing, SEM e Organic Search”, com 26.60%, 26,36% e 18.77% respetivamente, sendo “Instagram campaing” o melhor método para geração de leeds. Sendo o canal ideal “Instagram Campaing”

![venda de produtos de casa por canal](https://github.com/EveJr28/img/assets/168125942/17e9457d-8265-4efd-8df4-8c3a10a77f9d)

Nos produtos para casa se destacam a faixa etária entre 20 e 24 anos, com 9,90% das compras totais e o menor entre 70 e 74 anos com 1.99%

![qtd de venda de produtos de casa por faixa etaria](https://github.com/EveJr28/img/assets/168125942/ec0adef6-9cd0-4202-8135-9c2f7fff1802)

Na distinção de gênero por compra vemos um leve aumento com relação às outras duas categorias analisadas, sendo que o gênero feminino se sobressai nessa categoria com 50,18% das compras totais e os Masculino 49.82%

![percentual de vendas produ de casa por genero](https://github.com/EveJr28/img/assets/168125942/aa94e065-b2f6-47c8-8828-d0529c9f38b7)

Enquanto no NPS e o produto com maior ênfase estando com 5.01 de média geral quando vemos no detalhe entre homens e mulheres ficamos com a média de 5.01.

![media  nps produtos de casa por genero](https://github.com/EveJr28/img/assets/168125942/b5104f87-4d3b-4aa6-8790-60e0d5a7b20f)

- Clothing:

Na categoria Clothing(roupas), a estratégia que mais se destaca é “Instagram Campaing”, com 27.86% dos leads, seguidos por “Facebook Campaing” e “SEM” que juntos tem 53,51%(Sendo 26.80% De “Facebook Camapaing” e 26,71 de “SEM” os outros 18.63% São de Organic Search, Sendo o canal ideal “Instagram Campaing”.

![vendas de roupas por genero](https://github.com/EveJr28/img/assets/168125942/9bdf3b7d-0698-4e93-b782-ad6caa8022eb)

A faixa etária entre 20 e 24 anos são os maiores compradores com 10.04% dos produtos totais, e as pessoas entre 70 e 74 anos são as que menos efetuam compras sendo apenas 1,93% do total.

![qtd de vendas de roupas por idade](https://github.com/EveJr28/img/assets/168125942/9512d40c-b634-4f1e-a1e8-e5194a5b2897)

Nas vendas de roupas por gênero o gênero feminino se sobre sai com a vende de 50.56% enquanto o gênero masculino fica com 49,44%
![percentual de vendas de roupar por genero](https://github.com/EveJr28/img/assets/168125942/479b9fd7-b71d-471c-b602-aaabcd09d734)

Nas vendas de roupas por gênero o gênero feminino se sobre sai com a vende de 50.56% enquanto o gênero masculino fica com 49,44%

![percentual de vendas de roupar por genero](https://github.com/EveJr28/img/assets/168125942/477bbbbd-fc64-47e5-a800-6e72b17f42b6)

A média geral de NPS de 4.98 e destrinchando entre homens e mulheres as medias são 4,99 de média para as mulheres e 4,97 para homens

![media nps de roupas por genero](https://github.com/EveJr28/img/assets/168125942/51a7ee81-79d2-403b-8f94-d04e96c312aa)

- Analise geral:

O nosso público geral tem maior alcance através do “Instagram Campaing” sendo ele o método ideal para vendas dos produtos no geral, o publico da faixa etária entre 20 e 24 anos compõe no geral nossa maior pocentagem de aquisição como analisado no detalhe, o nosso NPC está entre 4,94 e 5,03.
Por faixa etária vemos que a faixa etária que melhor nos avalia está entre 15 e 19 anos com média de 5,03 e o pior está entre 70 e 74 com média de 4,94.

![MEdia de NPS por faixa etaria](https://github.com/EveJr28/img/assets/168125942/a168909e-6728-4de9-97f5-4ed9902592c6)

Podemos pensar em Campanhas para melhorar os nosso NPC tentando entender se a insatisfação foi com o produto ou com algo em nosso serviço em si 
O gênero feminino também compra mais nossos produtos do que o masculino ficando com 50.22% contra 49,78 % das compras. A faixa de 15 a 19 e 70 e 74 são as que menos compram conosco. 

![percentual de compra total por genero](https://github.com/EveJr28/img/assets/168125942/fd21b7b2-6b97-4190-85d9-995136118875)

Desta forma podemos impulsionar as vendas entre essas faixas. com maior atendimento humano para tentar melhorar nossa média tentando compreender e impulsionar nossos públicos menos engajados.

