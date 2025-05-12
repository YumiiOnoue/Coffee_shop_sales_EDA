# Análise Exploratória das Vendas de uma Cafeteria

## Objetivo do projeto
Este projeto tem como objetivo analisar o desempenho de vendas de uma cafeteria com três unidades distintas, utilizando dados transacionais para gerar insights estratégicos. Por meio da criação de dashboards interativos no Power BI, buscamos compreender o comportamento dos consumidores ao longo do tempo, identificar os produtos mais lucrativos, os horários de maior movimento, e comparar o desempenho entre as lojas. A análise visa gerando insights com os dados disponíveis e apoiar a tomada de decisões comerciais.

## Premissas do negócio
O banco de dados possui 149.116 transações de três lojas (Hell's Kitchen, Astoria e Lower Manhattan). 
A média de produtos por transação é de 1,44 e no máximo 8 produtos. 
O maior preço único é de $45 do café civete e preço mínimo é $0,80 de quatro produtos (calda de caramelo, calda de chocolate, calda de avelã e calda sem açúcar sabor baunilha.
O período da análise é de janeiro a junho de 2023.
Não há valores nulos nos dados. Desta forma, não foi necessário fazer o tratamento dos dados.

## Resultados
A análise exploratória da cafeteria foi realizada no Microsofr Power BI, o arquivo está anexado [aqui](Coffee_shop_sale.pbix) para baixar.

Separei os dados em três grupos, uma para análise geral, outro para análisar as lojas e por fim, uma análise por produto. 

Na visão geral, temos que essa cafeteria teve faturamento de $698,81 mil, total de 214 mil vendas e ticket médio de $3,26 nos seis primeiros meses de 2023.
Tanto a receita e as vendas aumentaram no período análise, passando de $80 mil em janeiro para $170 mil em junho.
As três lojas apresentam receitas superior a $230 mil, dando destaque para Hell's Kitchen que apresenta receita de $240 mil.
As quantidades médias de transações por hora variam entre 1,41 e 1,49. Sendo o período da abertura, as 6h, com mais movimento e as 19h
com menos movimento.

<img src="imagens/geral.jpeg" alt="Análise Geral" width="800" height="500"/>

Ao analisar as lojas, temos que todas elas tiveram aumento da receita no período analisado. Entretanto, observa-se que a loja Hell's Kitchen tem receita superior em todos os meses em comparação com as outras duas lojas. 
A categoria de produto que mais contribuiem para a receita das lojas é: café, chá, padaria e bebidas com chocolate. Porém, o grão de café, na Hell's Kitchen, apresenta receita superior em relação a loja de Astoria e Lower Manhattan.
O produto líder nas três lojas é o "Sustainably Grown Organic", tanto no tamanho grande e regular, e em seguida, temos os blends de chai tradicional, indicando preferência por bebidas diferenciadas e saudáveis.

Em relação ao horário das unidades, temos que Astoria tem período de funcionamento diferente, sendo entre as 7h e 19h, enquanto as outras duas lojas atendem entre as 6h e 20h, duas horas a mais que a unidade Astoria. Outro ponto que merece destaque é a transação média da Lower Manhattan, pois esta apresenta transações médias superiores em quase todos os horários, exceto as 13h e as 18h. Nesses dois horários, a unidade da Hell's Kitchen tem maior movimentação em suas vendas.
Já a unidade de Astoria, tem quantidades de transoções médias entre 1,36 e 1,44, e média mais alta de transações das Hell's Kitchen e Lower Manhattan são, respectivamente, 1,48 e 1,55 vendas por hora. 

<img src="imagens/por_loja.jpeg" alt="Análise por Loja" width="800" height="500"/>

Análise por produto

<img src="imagens/por_produto.jpeg" alt="Análise por Produto" width="800" height="500"/>


## Conclusão
