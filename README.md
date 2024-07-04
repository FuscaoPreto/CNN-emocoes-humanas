# CNN Emoções Humanas

Este projeto utiliza uma Rede Neural Convolucional (CNN) para classificar emoções humanas a partir de imagens. O modelo é treinado e testado usando o conjunto de dados FER2013.

## Estrutura do Projeto

O projeto é estruturado em um único arquivo Jupyter Notebook, cnn-fer2013-igor.ipynb.

## Como Executar

1. Clone o repositório para sua máquina local.
2. Certifique-se de ter todas as dependências necessárias instaladas.
3. Abra o arquivo cnn-fer2013.ipynb em um ambiente Jupyter Notebook.
4. Mude o caminho dos dados de teste e treino para seu novo caminho.
5. Execute todas as células do notebook para treinar e testar o modelo.
6. Execute camera.py para ver a detecção em tempo real.

## Detalhes do Modelo

O modelo é uma CNN que é treinada para classificar 7 diferentes emoções humanas: `disgust`, `surprise`, `angry`, `happy`, `neutral`, `sad`, `fear`. O modelo é salvo em [`model/ferNet.tf`](command:_github.copilot.openRelativePath?%5B%22model%2FferNet.tf%22%5D "model/ferNet.tf") sempre que a acurácia do modelo melhora.

## Conjunto de Dados

O conjunto de dados FER2013 é usado para treinar e testar o modelo. O conjunto de dados é dividido em conjuntos de treinamento e teste, e a distribuição das emoções em cada conjunto é exibida no início do notebook.

## Resultados

Os resultados do treinamento do modelo são exibidos no notebook, incluindo a acurácia e a perda do modelo para cada época.

## Contribuições

Contribuições para o projeto são bem-vindas. Por favor, faça um fork do repositório e crie um Pull Request com suas alterações.
