# Docker: Utilização prática no cenário de Microsserviços
Professor Denilson Bonatti, Instrutor - Digital Innovation One

Esse projeto cria vários microserviços em Docker.

Microserviços são muito importantes no contexto atual em que servidores monolíticos podem ser muito arriscados, tanto pela segurança quanto pelo desempenho.

O Docker é uma ferramenta que possibilita a utilização de containers para a execução de aplicativos.

Esses conteiners são como máquinas virtuais, porém já pré-montadas.

Um cluster é um aglomerado de computadores que trabalham juntos para realizar uma determinada tarefa.

O Docker Swarm é um recurso nativo do Docker que faz a gestão dos contanineres. Caso um conteiner caia, ele continua mantendo a aplicação rodando.

Foram criadas três principais aplicações nesse projeto, uma máquina com o servidor MySQL e uma com um servidor PHP.

Na sequência foi feito um teste do container para garantir que ele está aguentando as solicitações recebidas.

Depois foi criado um cluster para replicar 3 vezes cada microserviço. 

Por fim foi testado o cluster pra ver se ele estava aguentando as solicitações recebidas.

Os pré-requisitos são: Conhecimentos básicos em Linux, Docker e AWS.
