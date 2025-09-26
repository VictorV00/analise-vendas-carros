# Análise de Vendas de Carros Usados

Este projeto realiza uma análise descritiva de um conjunto de dados sobre vendas de carros usados para extrair insights sobre o mercado, incluindo estratégias de preços por fabricante e o impacto de características como quilometragem e tipo de combustível no valor dos veículos.

## Objetivo do Projeto

O objetivo principal foi praticar o processo de análise de dados do início ao fim, desde a limpeza e tratamento dos dados até a geração de conclusões de negócio. As principais questões investigadas foram:

* Quais fabricantes geram mais receita e quais vendem mais em volume?
* Qual a relação entre a quilometragem de um carro e seu preço de revenda?
* Como o tipo de combustível (Gasolina, Diesel, Híbrido) influencia o preço médio e a popularidade dos veículos?

## Ferramentas Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
    * **Pandas:** Para manipulação, limpeza e análise dos dados.
    * **Matplotlib / Seaborn:** Para a criação das visualizações gráficas.

## Principais Insights e Conclusões

Após a análise dos dados, chegamos às seguintes conclusões principais:

### 1. Estratégia de Mercado: Volume vs. Valor
A análise revelou duas estratégias de mercado distintas entre as marcas mais populares:
* Toyota possui a maior receita total de vendas, sendo 12.77% maior que a da Ford e 16.49% maior que a da VW.
* Isso ocorre mesmo com a Ford e a VW vendendo um volume maior de carros. A conclusão é que a Toyota aposta em um preço médio por veículo mais alto, focando em maior valor por unidade, enquanto as concorrentes focam em maior volume de vendas.
* Marcas como BMW e Porsche operam em um segmento de luxo, com alto preço médio e baixo volume de vendas.

### 2. Depreciação por Uso
Conforme o esperado, a análise confirmou uma forte correlação negativa entre a quilometragem e o preço. Gráficos de dispersão mostraram claramente que, quanto mais um carro é usado , menor é o seu valor de revenda.

### 3. Preço e Popularidade por Tipo de Combustível
Inicialmente, o valor total de vendas sugeria que os carros a gasolina eram os mais valiosos. No entanto, a análise do preço médio revelou uma história diferente:
* Os carros Híbridos são, em média, os mais caros.
* Seguidos pelos carros a Gasolina (Petrol) e, por último, os a Diesel.
* A conclusão é que o alto preço dos veículos híbridos é uma provável causa para que eles sejam os menos vendidos em volume, apesar de seu valor unitário elevado.
