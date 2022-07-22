# Estudo Apache Kafka

## O que é o Apache Kafka?

O [Apache Kafka](https://kafka.apache.org/) é uma plataforma distribuída de transmissão de dados que é capaz de publicar, subscrever, armazenar e processar fluxos de registro em tempo real. 

## Motivação

O Kafka é uma das plataformas de transmissão de eventos que vem mais sendo utilizada pelas empresas e desenvolvedores nos últimos anos devido a sua grande capacidade de performance. 

### E como funciona?

A imagem abaixo representa bem a seguinte ideia:
    
    -   Fulano é um Producer, ele publica mensagens no Tópico: GameNews 
    -   Ciclano é um Consumer, ele está consumindo (literalmente) as mensagens postadas no Tópico: GameNews
    -   Se Fulano enviar: GOL! Barcelona 1 x 0 Real Madrid 
    -   Ciclano receberá a mesma mensagem do lado de lá! -> GOL! Barcelona 1 x 0 Real Madrid 


![Exemplo simples](/assets/simple-kafka-dummies-sample-rsr.svg "Exemplo simples")

### Fontes
- [Apache Kafka](https://kafka.apache.org/)
- [O que é Apache Kafka?](https://www.redhat.com/pt-br/topics/integration/what-is-apache-kafka)
