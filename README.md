# OneBitCode Exchange

Aplicativo que converte o valor de uma moeda para outra qualquer.

* Rails 5.1.6

* ruby 2.4.0

* Clone o projeto para sua máquina

git clone git@github.com:marcelo080582/exchange.git

* Acesse a pasta do projeto

cd exchange

* Rode:

docker-compose build

* Crie um arquivo de configuração do banco de dados:

cp config/database.example.yml config/database.yml

* Crie o banco de dados.

docker-compose run website rails db:create

* Suba o servidor

docker-compose up

* Acesse no browser o endereço http://localhost:3000/
