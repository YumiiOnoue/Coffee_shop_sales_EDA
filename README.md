# ☕ Painel de Vendas da Cafeteria ☕

## Objetivo do projeto
Este projeto tem como objetivo analisar o desempenho de vendas de uma cafeteria com três unidades distintas, utilizando dados transacionais para gerar insights estratégicos. 

Por meio da criação de dashboards interativos no Power BI, buscamos compreender o comportamento das vendas ao longo do tempo, identificar os produtos mais lucrativos, os horários de maior movimento, e comparar o desempenho entre as lojas. 

A análise visa gerando insights com os dados disponíveis e apoiar a tomada de decisões comerciais.
- Os dados foram retirados do [Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

## Premissas do negócio
- O banco de dados possui 149.116 transações de três lojas (Hell's Kitchen, Astoria e Lower Manhattan). 
- A média de produtos por transação é de 1,44 e no máximo 8 produtos. 
- O maior preço único é de US$45 do café civete e preço mínimo é US$0,80 de quatro produtos (calda de caramelo, calda de chocolate, calda de avelã e calda sem açúcar sabor baunilha.
- O período da análise é de janeiro a junho de 2023.
- Não há valores nulos nos dados. Desta forma, não foi necessário fazer o tratamento dos dados.

## Resultados
A análise descritiva da cafeteria foi realizada no Microsofr Power BI, clique nesse [link](https://app.powerbi.com/view?r=eyJrIjoiYmMwMmQyNzgtMzJjMC00ZTViLThjNzAtYWRlODFhOGE0Y2E1IiwidCI6IjJlYjE0NDQ3LTQ0YWQtNDllZi04YjhmLTA5OWEzNTlhYjZkYSJ9)
para visualizar o dashboard.

Separei os dados em três grupos: uma análise geral, outra voltada para as lojas e, por fim, uma análise por produto.

Na visão geral, observamos que a cafeteria teve um faturamento de US$ 698,81 mil, totalizando 214 mil vendas e um ticket médio de US$ 3,26 nos seis primeiros meses de 2023. Tanto a receita quanto as vendas aumentaram ao longo do período analisado, passando de US$ 80 mil em janeiro para US$ 170 mil em junho.

As três lojas apresentaram receitas superiores a US$ 230 mil, com destaque para a unidade de Hell's Kitchen, que obteve US$ 240 mil em receita. As médias de transações por hora variaram entre 1,41 e 1,49, sendo o horário de abertura, às 6h, o de maior movimento, e o das 19h, o de menor fluxo.

<img src="imagens/geral.jpeg" alt="Análise Geral" width="800" height="500"/>

Ao analisar as lojas, observamos que todas apresentaram aumento de receita no período analisado. No entanto, destaca-se que a unidade Hell's Kitchen teve receita superior em todos os meses, em comparação com as outras duas lojas.

As categorias de produto que mais contribuem para a receita das lojas são: café, chá, padaria e bebidas com chocolate. Porém, o item grão de café, especificamente na unidade Hell's Kitchen, apresenta uma receita superior em relação às unidades de Astoria e Lower Manhattan.

O produto líder nas três lojas é o Sustainably Grown Organic, tanto nos tamanhos grande quanto médio. Em seguida, os blends de chai tradicional, também nos tamanhos grande e médio, aparecem como os mais vendidos, indicando uma preferência dos clientes por bebidas diferenciadas e saudáveis.

Em relação ao horário de funcionamento das unidades, a loja de Astoria opera das 7h às 19h, enquanto as unidades de Hell's Kitchen e Lower Manhattan funcionam das 6h às 20h, totalizando duas horas a mais de atendimento.

Outro ponto que merece destaque é a média de transações por hora da unidade Lower Manhattan, que é superior em quase todos os horários, exceto às 13h e às 18h, momentos em que a unidade de Hell's Kitchen apresenta maior movimentação.

Já a unidade de Astoria registra médias de transações por hora entre 1,36 e 1,44. As maiores médias de transações por hora nas unidades Hell's Kitchen e Lower Manhattan são, respectivamente, 1,48 e 1,55.

<img src="imagens/por_loja.jpeg" alt="Análise por Loja" width="800" height="500"/>

Na análise anterior, observou-se que os produtos com maior receita foram o Sustainably Grown Organic e os blends de chai. No entanto, ao analisar a quantidade vendida, esses dois produtos não aparecem entre os cinco mais vendidos.

Em primeiro lugar, temos o Earl Grey Rg, com 4.708 unidades vendidas, seguido por Dark Chocolate Lg (4.668 unidades) e Morning Sunrise Chai Rg (4.643 unidades). O Traditional Blend Chai Rg ocupa a sétima posição, com 4.512 unidades, enquanto o Sustainably Grown Organic Lg está em oitavo lugar, com 4.453 unidades vendidas.

Entre os produtos comercializados pelas cafeterias, alguns registraram receitas inferiores a US$ 10 mil, sendo eles:

- Chili Mayan: US$ 1.972,84
- Caramel Syrup: US$ 2.060,80
- Brazilian Organic: US$ 3.852,00
- Chocolate Chip Biscotti: US$ 6.748,96
- Almond Croissant: US$ 7.168,13

As categorias com mais de 1.500 unidades vendidas ao longo do período foram: café, chá, padaria, bebidas com chocolate e "Flavours". Essa última categoria só ultrapassou a marca de 1.500 unidades a partir de abril.

<img src="imagens/por_produto.jpeg" alt="Análise por Produto" width="800" height="500"/>

Todas as categorias apresentaram crescimento nas vendas, com destaque para café e chá, que mantiveram volumes superiores de vendas em todos os meses analisados. A categoria padaria, terceira colocada no ranking de vendas, registrou em junho 5.431 unidades vendidas, representando 74,7% a menos que o café e 66,9% a menos que o chá.

Entre os tipos de produtos, os três com maior renda média são da categoria orgânicos e premium:

- Grãos premium (US$ 43,40)
- Grãos orgânicos (US$ 20,50)
- Utensílios domésticos (US$ 14,15)


## Conclusão

Com essa análise, podemos concluir que as vendas das três lojas estão em crescimento, com destaque para a unidade de Hell's Kitchen, que apresenta uma receita levemente superior em comparação às demais.

Verifica-se também a necessidade de atenção ao horário de atendimento: a unidade de Astoria tem desempenho inferior de vendas em relação às outras duas, possivelmente devido ao menor tempo de funcionamento.

Outro ponto relevante é o desempenho dos produtos sustentáveis e orgânicos, que merecem destaque. Pode ser interessante investir em promoções ou programas de fidelidade focados nesses itens, aproveitando a preferência dos clientes.

Quanto às categorias, a padaria mostra potencial de crescimento e pode se beneficiar de um maior investimento estratégico.

Por outro lado, produtos como Chili Mayan, Caramel Syrup, Brazilian Organic, Chocolate Chip Biscotti e Almond Croissant apresentam baixo desempenho e precisam de maior atenção estratégica, seja para reposicionamento, ajuste de preço ou revisão da oferta.
