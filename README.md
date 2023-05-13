# Projeto_lista_Games_Java_Spring

DESENVOLVIMENTO DE PROJETO API REST EM JAVA SPRING BOOT

PROJETO DESENVOLVIDO EM ESTUDO SOBRE UM API REST QUE FORNECE:

1- LISTAGEM DE TODOS OS JOGOS,

2- LISTAGEM DE UM JOGO ESPECIFICO POR ID,

3- LISTAGEM DE JOGOS POR UMA LISTA ESPECIFICA,

4- MODIFICAÇÃO DA POSIÇÃO DE UM JOGO EM UMA LISTA ESPECIFICA;

----------------------------------------------

FORAM UTILIZADOS NESTE PROJETO, CONHECIMENTOS ESPECÍFICOS SOBRE AS SEGUINTES PLATAFORMAS:

LINGUAGEM JAVA

FRAMEWORK SPRING BOOT

POSTMAN

H2 DATABASE / SQL

DOCKER

IMPLEMENTAÇÃO EM NUVEM COM O SERVICE RAILWAY

GIT/GITHUB

----------------------------------------------

FORAM UTILIZADOS NESTE PROJETO OS CONCEITOS:

CLIENTE/SERVIDOR,

PADRAO REST PARA WEB,

ESTRUTURAÇÃO PROJETO JAVA SPRING

DATABASE, PADRAO CAMADAS,

PADRAO DTO,

RELACIONAMENTOS EM BASE DE DADOS,

CONSULTAS SQL,

DOCKER, DOCKER COMPOSE,

DEPLOY COM CI/CD, 

CORS, 

DESIGN E IMPLEMENTAÇÃO DE ENDPOINTS,

VERBOS HTTP.

----------------------------------------

ENDEREÇO DA IMPLEMENTAÇÃO NO RAILWAY:

projetolistagamesjavaspring-production.up.railway.app

----------------------------------------

ENDPOINTS PARA TESTE ( PODE SER UTILIZADO PARA TESTE O APLICATIVO POSTMAN):

/games     (listagem dos jogos)

/games/{id}    (listagem de um jogo especifico)

/lists   (listagem de uma lista especifica de tipo de game)

/lists/{id}/games   (lista um game especifico de uma lista especifica de tipo de game)

/lists/{id}/replacement  body{"sourceIndex":, "destinationIndex":}   ( modifica a posição especifica de um game na lista especifica {JSON})

---------------------------------------------

FOI REALIZADO O SEED PARA O BANCO DE DADOS COM A QUANTIDADE DE 10 JOGOS DIVIDIDOS EM UMA LISTA COM 2 GENEROS DE JOGOS.


