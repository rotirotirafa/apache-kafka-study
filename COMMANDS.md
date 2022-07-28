# Comandos

## kafka-topics.sh
Arquivo responsável pelos tópicos do Kafka

Flag   | Ação
--------- | ------
``--topic``| Nome do tópico
``--bootstrap-server`` | Servidor Kafka
``--partitions`` | Partições do tópico
``--list`` | Lista todos os tópicos
``--create``| Criar tópico
``--delete``| Excluí um tópico
``--alter`` | Altera config do tópico
``--describe``| Detalhes do tópico
``--replication-factor`` | Replicação do tópico

### Criar tópico kafka
    ./kafka-topics.sh --bootstrap-server 127.0.0.1:9092 --topic NomeTopicoAqui --create

## kafka-console-producer.sh
Arquivo responsável por criar e manipular producers

Flag   | Ação
--------- | ------
``--topic`` | Nome do tópico 
``--bootstrap-server`` | Servidor Kafka
``--sync`` | É uma flag que informa que as mensagens são produzidas de forma assíncrona
``--request-required-acks`` | Informa que necessita uma confirmação pelo producer
``--message-send-max-retries`` | Configuração máxima de tentativas de envio ao tópico


### Criar producer
    ./kafka-console-producer.sh --bootstrap-server 127.0.0.1:9092 --topic NomeTopicoAqui

## kafka-console-consumer.sh
Arquivo responsável por criar e manipular consumers

Flag   | Ação
--------- | ------
``--topic`` | Nome do tópico 
``--bootstrap-server`` | Servidor Kafka
``--from-beginning`` | Configuração para ler do inicio caso não houve uma leitura ou consumo
``--group`` | Grupo de consumers (se houver)
``--isolation-level`` | Configuração``read_committed`` para ler mensagens confirmadas, ``--read_uncommitted`` | para ler todas as mensagens (default)]
``--offset`` | Configuração do ponto de partida: ``earliest`` (início) e ``latest``(fim)