# Análise de Dados no Mercado Imobiliário de São Paulo

## Sumário
- [Descrição do Dataset](#descrição-do-dataset)
- [Variáveis Incluídas](#variáveis-incluídas)
- [Objetivo do Estudo](#Objetivo do Estudo)
- [Metodologia](#metodologia)
- [Análise Exploratória](#análise-exploratória)
- [Resultados Esperados](#resultados-esperados)
- [Visualizações](#visualizações)
- [Linguagem e Bibliotecas Utilizadas](#linguagem-e-bibliotecas-utilizadas)
- [Licença](#licença)
- [Contato](#contato)

## Descrição do Dataset
Este dataset contém informações detalhadas sobre apartamentos à venda na cidade de São Paulo, obtidas por meio de web scraping no site [vivareal.com.br](https://vivareal.com.br) e disponibilizadas na plataforma Kaggle. Ele oferece uma base rica para análises de padrões imobiliários, especialmente em relação a preços, localização e fatores socioeconômicos.

- **Número de Variáveis:** 23
- **Formato do Arquivo:** XLSX
- **Nome do Arquivo:** base_imoveis.xlsx

## Variáveis Incluídas
O dataset abrange diversas variáveis que influenciam o mercado imobiliário, incluindo:
- **Distância até o metrô mais próximo:** Medida em metros, reflete a proximidade do imóvel à estação de metrô mais próxima.
- **IDH (Índice de Desenvolvimento Humano) do bairro:** Índice que avalia a qualidade de vida na área, considerando fatores como educação, longevidade e renda.
- **Renda média do bairro:** Média da renda dos moradores na região.
- **Coordenadas geográficas:** Latitude e longitude do imóvel, para permitir análises espaciais.
- **Outras variáveis:** Informações adicionais como número de quartos, banheiros, área total, entre outras características relevantes.

## Objetivo do Estudo
Este estudo tem como objetivo analisar os padrões de moradias e imóveis na capital paulista, com foco em como o acesso facilitado a transportes urbanos, como o metrô, pode influenciar o aumento dos alugueis e dos preços de imóveis. A pesquisa também busca entender de que forma a localização afeta a segregação social, ao encarecer áreas com maior acessibilidade e excluir populações de menor poder aquisitivo dessas regiões. 

Para alcançar esses objetivos, será realizada uma análise detalhada dos dados de alugueis fornecidos pela maior empresa do setor imobiliário. O estudo pretende identificar os principais fatores que impactam os preços dos imóveis, seja para torná-los mais caros ou mais acessíveis, levando em consideração aspectos como infraestrutura e proximidade com transporte público.

Além disso, a pesquisa irá mapear os bairros mais caros da cidade de São Paulo, verificando a correlação entre o valor dos imóveis e a proximidade dos centros de acessibilidade urbana, como estações de metrô e linhas de ônibus. Dessa forma, será possível compreender melhor os efeitos do planejamento urbano sobre o mercado imobiliário e as disparidades sociais.

## Metodologia
A análise será conduzida utilizando as seguintes abordagens:
- **Análise Estatística:** Serão realizados testes de correlação e outras análises estatísticas para examinar as relações entre as variáveis.
- **Visualização de Dados:** Serão criados gráficos e tabelas para ilustrar os resultados de maneira clara e compreensível.

## Análise Exploratória
Na fase exploratória, as seguintes atividades serão realizadas para obter insights iniciais:
- **Análise Descritiva:** Cálculo de estatísticas descritivas, como média, mediana e desvio padrão para as variáveis numéricas.
- **Identificação de Outliers:** Detecção de outliers em variáveis como preço e renda média.
- **Visualização de Distribuições:** Criação de histogramas e boxplots para visualizar as distribuições das variáveis principais.
- **Análise de Correlação:** Estudo das correlações entre variáveis para entender melhor as inter-relações e identificar possíveis padrões.

## Resultados Esperados
Espera-se que a análise revele padrões significativos que influenciem os preços dos apartamentos. Além disso, insights sobre como a localização e características dos imóveis impactam a valorização serão gerados, auxiliando na compreensão das dinâmicas do mercado imobiliário em São Paulo.

## Visualizações
Serão criadas as seguintes visualizações para apoiar a análise:
- **Gráficos de Dispersão:** Para analisar a relação entre o preço dos imóveis e a distância ao metrô.
- **Histogramas:** Para visualizar a distribuição dos preços e da renda média dos bairros.
- **Heatmaps de Correlação:** Para entender as inter-relações entre as variáveis, destacando correlações fortes.

## Linguagem e Bibliotecas Utilizadas
- **Linguagem de Programação:** Python
- **Bibliotecas Python:**
  - NumPy: Para manipulação de arrays e cálculos numéricos.
  - Matplotlib: Para visualização gráfica dos dados.
  - Pandas: Para manipulação e análise dos dados.
  - Seaborn: Para criação de gráficos avançados e visualizações detalhadas.

## Licença
Este dataset é disponibilizado para fins de estudos e projetos acadêmicos. Não há restrições para o uso, de acordo com as diretrizes do criador, disponíveis no Kaggle.

## Contato
Para mais informações ou dúvidas, entre em contato com o criador do dataset através do fórum do Kaggle ou diretamente na [página do dataset](https://www.kaggle.com/datasets/jlgrego/apartamentos-venda-na-cidade-de-sao-paulo-sp).

### Colaboradores Alunos
- Felipe Fagion Longarini 
- João Pedro Daltro Rodrigues 
- Diogo Moreira Poltosi Rezende 
- Lucas Oliveira
- Gustavo Rosa Arizona

### Professor:
Thiago Graziani Traue 

### Professor Tutor:
Vinicius Piro Barragam
 

  

![Imagem de Exemplo](https://tecimob.com.br/blog/wp-content/uploads/2024/02/avaliacao-de-imoveis-2.jpg)
