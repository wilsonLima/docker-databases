docker-databases
=========

Containers de alguns bancos de dados para testes.


Lista de banco de dados
------------

- MongoDB versão 4.4.5
- MySQL versão 8
- Neo4j versão 6.2.3
- Postgresql versão 13 com Pgadmin 4
- Redis versão 6.2.3


Script para criar as pastas dos volumes
------------

    ./create_dirs.sh


Script para subir o container de uma database (dentro de cada pasta)
------------

    ./start.sh


Script para destruir o container de uma database (dentro de cada pasta)
------------

    ./stop.sh


License
-------

MIT