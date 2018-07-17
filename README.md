# the_healthy_adapter
Microservice with connection to RabbitMQ for consuming json message, that contains health information about other microservices. With each message the service should format the message to the standard prometheus format. So when prometheus probes this service, the service should respond back with health for itself and all other services.
