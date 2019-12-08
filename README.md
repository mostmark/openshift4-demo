# Demo Notes

Kafka Demo

bin/kafka-console-producer.sh --broker-list localhost:9092 --topic my-topic

Ctrl+c

bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic my-topic --from-beginning

Ctrl+c

Quarkus Demo

echo '-w "\n"' >> ~/.curlrc

curl -O https://raw.githubusercontent.com/mostmark/quarkus1/master/hello-quarkus-1.0-SNAPSHOT-runner

./hello-quarkus-1.0-SNAPSHOT-runner

bash -c "while [ 0 ]; do curl http://localhost:8080/hello;done"
