# Module 8: Software Architectures
## Tutorial Advanced Programming 2023/2024 Genap

* Nama  : Tengku Laras Malahayati
* NPM   : 2206081641
* Kelas : A

## Reflection
### How many data your publisher program will send to the message broker in one run?

There are 5 data that my publisher program will send to the message broker in one run. It can be seen inside the `main` function that there are 5 user_created data.

### The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

It means that Subscriber and Publisher are connected to the same AMQP protocol, which runs on the default port 5672.

## Running RabbitMQ as Message Broker

![RabbitMQ as Message Broker](image/RabbitMQ.png)

## Sending and Processing Event

![Sending and Processing Event](image/sending%20request.png)

The Publisher sends data to the message broker which is the received by the Subscriber when RabbitMQ is running and both programs (Publisher & Subscriber) are executed (using `cargo run`). As shown in the image above, the Publisher transmits the data to the message broker and the Subscriber successfully retrieves it.