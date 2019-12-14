docker-databases
=========

Containers de alguns bancos de dados para testes.


Lista de banco de dados
------------

- MongoDB versão 4.2
- MySQL versão 8
- Neo4j versão 3.5
- Postgresql versão 12 com Pgadmin 4
- Redis versão 5.0


Script para criar as pastas dos volumes
------------

    ./create_dirs.sh


Script para subir os container de uma database (dentro de cada pasta)
------------

    ./start.sh


Script para destruir os container de uma database (dentro de cada pasta)
------------

    ./stop.sh


License
-------

MIT