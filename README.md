# Dashboad Analítico de Vendas Globais
## 📖 Descrição:
Este projeto consiste na criação de um dashboard interativo no Power BI para análise de vendas, utilizando diferentes tipos de visualizações para responder a cinco perguntas-chave sobre o desempenho das vendas.

## Perguntas: 
1) **Qual o valor total vendido?**
R: Foi utilizado o CARTÃO, resultando em um valor de 12,64 milhões.
A coluna utilizada para a criação foi: Total_Vendas.

2) **Quantas vendas foram realizadas por categoria de produto?**
R: Utilizou-se um gráfico de pizza.
As colunas utilizadas foram: Categoria e ID_Pedido.

3) **Quantas vendas foram realizadas por país considerando a prioridade de entrega?**
R: Foi utilizado um gráfico de barras empilhadas (geralmente utilizado quando há mais de três informações a serem mostradas).
No eixo Y, utilizou-se a coluna País; no eixo X, a coluna ID_Pedido; e na legenda, a coluna Prioridade.

4) **Qual foi a média de desconto nas vendas por subcategoria de produto?**
R: Utilizou-se um gráfico de barras clusterizadas.
No eixo X, utilizou-se a coluna SubCategoria; no eixo Y, a coluna Desconto (foi necessário calcular a soma para obter a média).

5) **Quais países tiveram maior média de valor de venda? Demonstre em um mapa.**
R: Utilizou-se um mapa.
A coluna utilizada foi: País para localização, e Total_Vendas para o tamanho da bolha (foi necessário calcular a soma para obter a média).
Foi estabelecido um filtro com a especificação: Maior que 250.
Observação: O dashboard deve permitir ao usuário filtrar os dados por ano, segmento e país. Para isso, foram utilizados segmentações de dados para Ano, Segmento e País.

## Resumo:
✅Total de Vendas: Valor total vendido utilizando cartão (R$ 12,64 milhões).

✅ Vendas por Categoria de Produto: Exibidas em um gráfico de pizza.

✅ Vendas por País e Prioridade de Entrega: Apresentadas em um gráfico de barras empilhadas.

✅ Média de Desconto por Subcategoria: Visualizada por meio de um gráfico de barras clusterizadas.

✅ Média do Valor de Vendas por País: Representada em um mapa interativo.

## 🚀 Tecnologias Utilizadas:
- Excel
- Power BI

## 💻 Como Executar o Projeto:
- Power BI
