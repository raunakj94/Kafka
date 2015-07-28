
# Kafka

http_server.go --a RESTful web server written in Golang wih embedded boltDb using the mux package.


kafka_producer.go-- a kafka producer in golang  using the shopify package reading events from AD servers restful endpoints and coverting them to avro events and pushing them to Apache Kafka log to different topics AD,Win and Clicks.


http_consumer.go--a kafka producer using the shopify package which consumes the Avro events from Apache Kafka and deserialize and store thems in embedded boltDb in buckets of AD,Win and Clicks respectively.
