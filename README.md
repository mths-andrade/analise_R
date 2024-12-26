# Análise descritiva no R

Vamos realizar uma análise descritiva no R. Criei um notebook no Google Colab e usei a seguinte [tabela de dados](https://github.com/mths-andrade/analise_R/blob/dce9529275859cbc62e846a3d6f1f547c020414b/dados.xlsx).

O projeto que desenvolveremos é sobre os preços de moradias em São Paulo. Trabalharemos com diversas informações dessas moradias, como:

Endereço (address): O endereço do imóvel;

Distrito (district): O distrito onde o imóvel está localizado;

Área (area): A área do imóvel em metros quadrados;

Quartos (bedrooms): O número de quartos na propriedade;

Garagem (garage): O número de vagas de estacionamento disponíveis na propriedade;

Aluguel (rent): O valor do aluguel mensal do imóvel;

Tipo (type): O tipo do imóvel (apartamento, casa, estúdio, etc.);

Total (total): O custo total do imóvel, incluindo aluguel, impostos e outras taxas.

Para iniciar nosso projeto, realizaremos a importação da base de dados e também o tratamento desses dados, como lidar com valores nulos que estão distribuídos dentro dos nossos registros. A maioria do projeto foi escrita usando o pacote Tidyverse, muito útil para a manipulação de dados.

Em seguida, começaremos a avaliar esses dados utilizando medidas de tendência central, como média e mediana, além de utilizar o desvio padrão para entender como nossos dados estão se comportando.

Utilizaremos também a visualização de dados, ou seja, gráficos de barra, caixa (boxplot) e dispersão para nos auxiliar a entender a distribuição dos dados e o comportamento das variáveis. Além disso, faremos uso de tabela de frequência e histograma para compreender a frequência dos dados.

Por fim, montaremos nossa matriz de correlação para entender como as variáveis se relacionam e desenvolveremos nosso modelo de regressão linear, além de realizar previsões, que é o objetivo do nosso projeto.
