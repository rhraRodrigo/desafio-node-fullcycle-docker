Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

<h1>O retorno da aplicação node.js para o nginx deverá ser:</h1>

Full Cycle Rocks!

+ Lista de nomes cadastrada no banco de dados.

Tudo deverá estar funcionando e disponível na porta: <b>localhost:8080</b>.

<h1>Para executar o projeto, faça os passos abaixo:</h1>

-> git clone https://github.com/rhraRodrigo/desafio-node-fullcycle-docker.git

-> cd desafio-node-fullcycle-docker

-> docker-compose up -d
