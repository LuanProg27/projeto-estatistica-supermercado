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