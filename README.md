# Análise Exploratória de Dados de Logística da Loggi

Este projeto realiza uma análise exploratória de dados sobre os desafios logísticos enfrentados pela Loggi, uma startup brasileira referência em tecnologia aplicada ao setor de logística. O estudo aborda questões como a otimização de rotas de entrega, alocação eficiente de entregas em veículos com capacidade limitada e gestão de tempos e custos.

## 1. Contexto

A Loggi é uma startup unicórnio brasileira fundada em 2013, focada em soluções logísticas inovadoras. Com uma trajetória que começou nas entregas de documentos, a Loggi expandiu rapidamente suas operações para o e-commerce e o setor de entregas de alimentos, posicionando-se como uma das líderes no mercado de logística do Brasil.

### Objetivos da Análise

Este projeto visa explorar dados logísticos para:
* Identificar padrões e oportunidades de otimização em rotas de entrega.
* Analisar a capacidade de veículos em relação às demandas de entrega.
* Observar como fatores como localização e capacidade impactam o desempenho logístico.

## 2. Pacotes e Bibliotecas Utilizados

Para manipulação, análise e visualização dos dados, foram utilizadas as seguintes bibliotecas Python:
* `json`: manipulação de dados em formato JSON.
* `geopandas` e `geopy`: para processamento e manipulação de dados geoespaciais.
* `folium`: para visualização de dados geoespaciais em mapas interativos.
* `matplotlib.pyplot` e `seaborn`: para visualização de dados e criação de gráficos.
* `numpy` e `pandas`: para manipulação e análise de dados.

  Instale as dependências com:

  >bash
  >
  >pip install geopandas geopy folium matplotlib numpy pandas seaborn

## 3. Exploração de Dados

  Os dados são fornecidos em formato JSON, onde cada instância representa um conjunto de entregas associadas a um hub regional da Loggi. As entregas são atribuídas a veículos específicos, e os dados incluem:
  * Informações de geolocalização (latitude e longitude) para os pontos de entrega.
  * Capacidade dos veículos e tamanho das entregas.
  * Cidades e regiões associadas a cada entrega.

## 4. Análises Realizadas

 O projeto inclui análises e visualizações como:
 * **Mapas de Calor (Heatmaps)**: para visualizar a concentração de entregas por área geográfica.
 * **Gráficos de Barras e Distribuição**: para explorar a distribuição de entregas e capacidades de veículos.
 * **Visualizações Geoespaciais**: com o uso de folium e geopandas, para mapear as rotas e identificar pontos críticos.

## 5. Exemplos de Dados e Visualizações

 ### Estrutura dos Dados
 Abaixo está uma amostra dos dados analisados no projeto, mostrando algumas colunas do DataFrame principal:

   ![image](https://github.com/user-attachments/assets/3e0ff4cd-fed5-4bbc-9cc7-51fe71f96351)

 ### Visualização dos Dados
 A seguir, um gráfico representativo que mostra a distribuição das entregas por região, permitindo visualizar as áreas com maior concentração de entregas:

 ![image](https://github.com/user-attachments/assets/1a997e63-511e-4e19-913a-55da465bd12a)


## 6. Principais Conclusões

 As conclusões deste projeto destacam as áreas de oportunidade para melhorias na logística da Loggi, como a otimização de rotas em regiões com maior demanda e a alocação mais eficiente de veículos.

## 7. Como Executar o Projeto

 1. Clone o repositório e abra o notebook Projeto1.ipynb no Google Colab ou em um ambiente Jupyter.
 2. Certifique-se de que todas as bibliotecas necessárias estão instaladas.
 3. Execute o notebook para gerar as visualizações e analisar os dados.

## 8. Contato

 Para dúvidas e sugestões, sinta-se à vontade para entrar em contato!
