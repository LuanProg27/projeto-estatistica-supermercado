# Projeto M13 - Fundamentos da Descoberta de Dados

Análise estatística descritiva de produtos de um supermercado do Chile (EBAC - Profissão Cientista de Dados).

## O que foi feito
- Média, mediana e desvio padrão de Preco_Normal por categoria
- Boxplot e identificação de outliers da categoria com maior desvio (lacteos)
- Gráfico de barras da média de desconto por categoria
- Mapa interativo (treemap) da média de desconto por categoria e marca

## Arquivos
- `Profissao Cientista de Dados M13 Projeto.ipynb`: notebook com o código e as análises
- `base_supermercado.csv`: base de dados
- `boxplot_lacteos.png`, `barras_desconto_categoria.png`, `mapa_desconto.png`: gráficos
- `mapa_desconto.html`: mapa interativo (baixe o arquivo e abra no navegador)

## Como executar
```
pip install pandas matplotlib plotly nbformat
```
Abra o notebook e execute as células em ordem.

## Observação sobre os dados
294 dos 1.107 produtos têm Preco_Normal = 0 (preço normal não registrado). Eles foram mantidos na análise.

## Principais resultados
- Em 6 das 7 categorias a média de Preco_Normal fica acima da mediana; a exceção é comidas-preparadas.
- A categoria com maior desvio padrão é lacteos (3925,8). Nela a média (2385,2) é mais que o dobro da mediana (989,0), o que indica uma distribuição assimétrica, com poucos produtos de preço muito alto.
- O boxplot de lacteos mostra 43 outliers, todos acima de 6119, quase todos packs de 12 unidades de leite e leite em pó em embalagens grandes.
- Congelados e belleza-y-cuidado-personal têm as maiores médias de desconto. Frutas, verduras e instantaneos-y-sopas não têm nenhum produto com desconto.