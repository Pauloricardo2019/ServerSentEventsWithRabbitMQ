# ServerSentEventsWithRabbitMQ
API using Server-Sent Event, consuming data from a rabbitMQ

# Primeiramente, starta o docker-compose com o comando: docker-compose up -d;  inicie o programa no path cmd/main.go
  ### abra no seu navegador o RabbitMQ no caminho: localhost:15672; user:guest, pass:guest
  ### abra no seu navegador no path localhost:9090
  ### para ver as mensagens em tempo real, abra o rabbitMQ e crie uma queue com o nome "msgs", após isso é só publicar novas mensagens na queue
