# Instruções

Para inicializar o Kafka, acesse a pasta e rode os comandos:

## Run ZooKeeper Server
    ./bin/zookeeper-server-start.sh config/zookeeper.properties


## Run Kafka Server
    ./bin/kafka-server-start.sh config/server.properties

OBS: ``./bin/nome-arquivo.sh`` é o comando que executa o server, e ``config/arquivo.properties`` é o arquivo de configuração que pode ser alterado de acordo com a necessidade