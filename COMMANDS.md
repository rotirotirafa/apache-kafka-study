# Comandos

## kafka-topics.sh
Arquivo bat responsável pelos tópicos do Kafka

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

