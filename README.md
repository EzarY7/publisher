Mochammad Ezar Yudha 2206046746
<h1>Tutorial 8</h1>
<h2>Reflection 1</h2>
<h3>How many data your publlsher program will send to the message broker in one
run?</h3>
The publisher program will send 5 data messages to the message broker in one run. Each call to p.publish_event sends one message.
<h3>The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?</h3>
The URL amqp://guest:guest@localhost:5672 is used to connect to the message broker using the AMQP protocol. It is same as in the subscriber program. Both are connecting to the same message broker.