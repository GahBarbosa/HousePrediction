# Previsão de Preços de Imóveis

Este projeto tem como objetivo construir um modelo preditivo para estimar o preço de venda de imóveis com base em suas características estruturais e localização. Utilizando Machine Learning, este modelo busca fornecer estimativas precisas de preços para auxiliar no processo de compra, venda e avaliação de propriedades.

## Visão Geral

O modelo é treinado utilizando um conjunto de dados que inclui variáveis como metragem, qualidade da construção, número de cômodos, ano de construção e outras características dos imóveis. A abordagem de Machine Learning permite fazer previsões baseadas em dados históricos, identificando padrões que impactam o valor dos imóveis.

## Objetivos

* Desenvolver um modelo preditivo que estime com precisão o preço de imóveis.
* Analisar as variáveis que mais influenciam o preço de venda.
* Avaliar o desempenho do modelo utilizando métricas como R², MAE (Erro Absoluto Médio) e RMSE (Erro Quadrático Médio).
* Realizar a visualização dos resíduos para entender melhor o comportamento do modelo e identificar potenciais problemas.


## Como Executar o Projeto

### Requisitos

* Python 3.x
* Bibliotecas:

  * pandas
  * numpy
  * scikit-learn
  * matplotlib
  * seaborn

### Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/projeto-previsao-precos-imoveis.git
   ```

2. Execute o notebook principal:

   ```bash
   jupyter notebook HousePricePrediction.ipynb
   ```

### Estrutura de Arquivos

* `HousePricePrediction.ipynb`: Notebook com o código para análise de dados, treinamento do modelo e avaliação.
* `data/`: Pasta contendo o arquivo de dados utilizado (`imoveis.csv` ou similar).
* `requirements.txt`: Arquivo com as dependências do projeto.

## Contribuições

Contribuições são bem-vindas! Se você tem sugestões de melhorias ou novos recursos, por favor, envie um **pull request** ou crie uma **issue**.