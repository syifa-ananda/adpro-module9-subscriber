## What is amqp?  
AMQP (Advanced Message Queuing Protocol) is just a set of rules that lets different apps talk to each other by sending messages through a broker (like RabbitMQ). It makes sure messages get where they need to go and handles things like retries and confirmations for us.

## What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for? 
- **first `guest`**: the username we log in with  
- **second `guest`**: the password for that user  
- **`localhost:5672`**: the address (our own computer) and port (5672 is RabbitMQ’s default) where the broker is running  
