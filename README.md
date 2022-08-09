# Projeto de Mestrado


Análise Comparativo de Técnicas de Redes Neurais Recurrentes na Predição de Testes de Software em Aplicativos Móveis

* LSTM
* Bi-LSTM
* LSTMConv1D
* LSTMConv2D


# passos para rodar o script de treinamento
para executar o train v1 precisa do python 3.6 e tensorflow 1.12

## Preparar o ambiente e ativar os ambientes 

### seguir os passos nesses dois tutoriais para criar um ambiente virtual com python 3.6.2(opcional, caso tenha o seu gerenciador de ambiente preferido)

https://felipetoscano.com.br/gerenciando-versoes-python-com-pyenv-no-ubuntu/

https://felipetoscano.com.br/ambientes-virtuais-em-python-com-pyenv-virtualenv-no-ubuntu/

## Instalar as dependências, para isto rode o comando:
entre na pasta train/:
cd train/

pip install -r requirements.txt

## Executar o arquivo train.py

python train.py -c config.json
