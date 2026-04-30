Apache Kafka is a tool used to move data around between systems quickly and reliably.

Example: Imagine a messaging system
    One system sends messages, like letters.
    Another system receives them.
    Kafka acts like the post office, making sure messages get delivered fast and in order.

What Kafka actually does:
    It lets applications send data (producers)
    It stores that data temporarily
    Other applications read that data (consumers)

Real life example

Think of a food delivery app:

  When you place an order, an event is created
  Kafka passes that event to:
    - Restaurant system 
    - Delivery system
    - Notification system
All of them get the same information instantly through Kafka.

Why people use Kafka
    - Handles huge amounts of data
    - Works in real time (almost instantly)
    - Very reliable (doesn’t easily lose data)
    - Can connect many systems together
    
Producer (the sender)

A producer is anything that sends data into Kafka.

  - It creates messages (called events)
  - It pushes those messages to Kafka topics

Example:

  - A food app sends a new order → that app is the producer
  - A website sending user activity logs is also a producer

Think of a producer as a person dropping letters into a mailbox

Consumer (the receiver)

A consumer is anything that reads data from Kafka.

  - It subscribes to topics
  - It processes the messages

Example:

  - A delivery system reading new orders
  - A notification service sending SMS/email
