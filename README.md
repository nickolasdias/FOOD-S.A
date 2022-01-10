# Projeto de Análise de Dados: Empresa FOOD-S.A

A FOOD S.A é a empresa número 1 para fabricar produtos a serem preparados em casa. Entretanto, em 2020, a nova diretoria da empresa decidiu produzir e comercializar queijo. A ideia era complementar o portfólio da empresa e aumentar sua participação no mercado. Desde 2020, a empresa vem investindo muitos recursos para ser uma empresa inovadora. Por essa razão, começou a manter um registro de suas transações em um sistema ERP com o objetivo de utilizar esses dados para obter alguns insights que ajudassem a desenvolver melhores produtos.

Um dos maiores problemas que a empresa tem é a falta de precisão quando um novo produto é lançado. Normalmente a expectativa é muito diferente da realidade e gera alguns alguns desperdícios e alguns clientes não estão a vontade. Hoje, a empresa quer usar os dados para resolver algumas questões. Logo, contrata um analista de dados para responder as seguintes questões:

## Questões

- Foi uma boa decisão comercializar queijo em 2020 ? Quais marcas de queijo são as mais importantes ?
- Qual canal/planta é crítico para a empresa ? Sua importância depende da marca ?
- A empresa quer lançar uma nova marca de queijo, mas não sabe se lança com produtos de 100 gramas por unidade ou 200 gramas por unidade. Qual delas pode-se recomendar ? E quantas toneladas de produto recomenda-se a produção para o primeiro mês de venda deste novo produto ?

## Glossário

•	CHANNEL - Ele representa o canal onde um produto é comercializado. Um Canal é um grupo de clientes com características similares.
•	SOLD_TO - É o ID para identificar cada cliente.
•	MATERIAL - É o ID para identificar cada produto.
•	CODE_TO_GROUP - Às vezes, dois produtos iguais têm códigos diferentes. Para juntar as bainhas, usamos este código.
•	SUB_BRAND - Submarca para o produto.
•	BRAND - Marca para o produto.
•	CATEGORY - Categoria do produto. A categoria é o grupo no mercado onde um produto se compila. Por exemplo: bebidas é onde todos os refrigerantes são compósitos.
•	TYPE - Tipo do produto: Regular ou leve.
•	WEIGHT_PER_UNIT - Mostra o peso da unidade de um produto.
•	PLANT - É o código do armazém de cais onde o produto foi entregue.
•	PERIOD - Ano/Mês em que o produto foi entregue (formato AAAAMM).
•	KG - Quantidade de produto vendido. As unidades são diferenciadas por UNIT_OF_WT.	
