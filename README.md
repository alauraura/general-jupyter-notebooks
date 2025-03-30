# Análise de Dados de Produtos da Adidas

## Introdução

A análise de dados desempenha um papel fundamental no setor de varejo, permitindo identificar padrões de consumo e otimizar estratégias de precificação e marketing. Neste estudo, exploramos um conjunto de dados de produtos da Adidas, com o objetivo de entender melhor as categorias mais vendidas, a variação de preços e a influência dos descontos no engajamento dos consumidores.

Para isso, aplicamos técnicas de análise exploratória de dados (EDA), utilizando visualizações estatísticas para detectar tendências e padrões. Além disso, buscamos responder a perguntas-chave, como:

- Quais são as categorias de produtos mais comercializadas?
- Como os preços variam entre diferentes tipos de produtos?
- Produtos com desconto geram mais engajamento dos clientes?
- Existe um "ponto ótimo" de desconto que maximiza a interação dos consumidores?

A partir dessas análises, esperamos fornecer insights que possam ser utilizados para otimizar estratégias de precificação e promoções no mercado de moda esportiva.

## Metodologia

O estudo foi realizado com base em técnicas de análise exploratória de dados (EDA), utilizando bibliotecas como Pandas, Matplotlib e Seaborn para gerar visualizações e detectar padrões nos dados. A análise foi focada nos seguintes aspectos:

- **Variação de Preços:** Análise da faixa de preços dos produtos e identificação de outliers.
- **Engajamento e Descontos:** Investigação da relação entre produtos com e sem desconto e a quantidade de avaliações recebidas.
- **Padrões de Consumo:** Identificação das categorias de produtos mais populares e a relação entre o tipo de produto e os descontos.

## Conclusão

Nesta análise, exploramos os padrões nos produtos da Adidas, com foco nas categorias mais vendidas, variação de preços e a relação entre descontos e engajamento dos consumidores.

### Principais descobertas:
- A maioria dos produtos possui preços entre 20 e 65 USD, com um grupo de outliers na faixa de 180 a 185 USD.
- Sapatos tendem a ter preços mais elevados e maior variação de valores, enquanto acessórios são mais acessíveis, ficando abaixo dos 50 USD.
- Termos como "Shoes ZX", "Boost Shoes", "Hoodie" e "Tee" aparecem com frequência nos nomes dos produtos, indicando as linhas mais populares no momento da coleta dos dados.

### Descontos e Engajamento:
- Produtos com desconto tendem a receber cerca de 8 vezes mais avaliações do que aqueles sem desconto.
- A maioria dos produtos tem um desconto entre 25% e 30%, mas o maior engajamento ocorre na faixa de 30% a 40%.
- Descontos superiores a 40% não necessariamente aumentam o número de avaliações, sugerindo um possível ponto ótimo para maximizar vendas e engajamento.

### Reflexões finais:
Os insights obtidos podem ajudar na definição de estratégias de precificação e promoção para maximizar o impacto das vendas. A relação entre descontos e engajamento reforça a importância de definir faixas de desconto estratégicas para incentivar o consumo sem comprometer a margem de lucro.

Futuros estudos poderiam incluir dados de vendas reais para validar melhor a relação entre descontos e desempenho dos produtos.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/repositorio.git
