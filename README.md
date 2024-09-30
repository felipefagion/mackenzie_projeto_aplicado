# Análise de Dados no Mercado Imobiliário

## Sumário
1. [Descrição do Dataset](#descrição-do-dataset)
2. [Variáveis Incluídas](#variáveis-incluídas)
3. [Objetivo do Dataset](#objetivo-do-dataset)
4. [Metodologia](#metodologia)
5. [Análise Exploratória](#análise-exploratória)
6. [Resultados Esperados](#resultados-esperados)
7. [Visualizações](#visualizações)
8. [Instruções de Execução](#instruções-de-execução)
9. [Licença](#licença)
10. [Contato](#contato)
11. [Imagem de Exemplo](#imagem-de-exemplo)

## Descrição do Dataset

Este dataset contém informações sobre apartamentos à venda na cidade de São Paulo. Os dados foram coletados por meio de web scraping de [vivareal.com.br](https://vivareal.com.br) e foram disponibilizados na plataforma [Kaggle](https://www.kaggle.com).

- **Número de Variáveis:** 23
- **Formato do Arquivo:** XLSX
- **Nome do Arquivo:** `base_imoveis.xlsx`

## Variáveis Incluídas

O dataset inclui as seguintes variáveis:

- **Distância até o metrô mais próximo:** Distância em metros até a estação de metrô mais próxima.
- **IDH (Índice de Desenvolvimento Humano) do bairro:** Índice que mede o desenvolvimento humano da área.
- **Renda média do bairro:** Média de renda dos residentes no bairro.
- **Coordenadas geográficas:** Latitude e longitude do imóvel.
- **Outras variáveis:** Informações adicionais relevantes sobre os apartamentos, como número de quartos, banheiros, área total, etc.

## Objetivo do Dataset

O objetivo deste dataset é permitir a análise de padrões e fatores relacionados a apartamentos à venda em São Paulo. Possíveis aplicações incluem:

- **Análise de Preços:** Compreender como o preço dos apartamentos varia com base em diferentes fatores.
- **Estudo de Fatores Influentes:** Analisar quais variáveis (como a distância ao metrô, IDH, renda média) afetam o valor dos imóveis.
- **Análise Espacial e Socioeconômica:** Explorar padrões espaciais e socioeconômicos relacionados ao mercado imobiliário.

## Metodologia

A análise será realizada utilizando os seguintes métodos:

- **Análise Estatística:** Testes para verificar a correlação entre variáveis.
- **Visualização de Dados:** Criação de gráficos e tabelas para ilustrar os dados e resultados.

## Análise Exploratória

Nesta fase, serão realizadas diversas análises para entender melhor o conjunto de dados, incluindo:

- **Análise Descritiva:** Cálculo de estatísticas descritivas (média, mediana, moda, desvio padrão) para as variáveis numéricas.
- **Análise de Outliers:** Identificação de possíveis outliers nas variáveis mais relevantes, como preço e renda média.
- **Análise de Distribuições:** Visualização das distribuições das variáveis principais para compreender a forma dos dados (ex: histogramas, boxplots).
- **Análise de Correlação:** Avaliação das correlações entre variáveis para identificar relações significativas.

## Resultados Esperados

Espera-se identificar padrões que influenciam os preços dos apartamentos, além de insights sobre como fatores como localização e características do imóvel impactam a valorização.

## Visualizações

Serão realizadas as seguintes visualizações:

- Gráficos de dispersão para analisar a relação entre preço e distância ao metrô.
- Histogramas para visualizar a distribuição de preços e renda média.
- Heatmaps de correlação para entender as inter-relações entre variáveis.