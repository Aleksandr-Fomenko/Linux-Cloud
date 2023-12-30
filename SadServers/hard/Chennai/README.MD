<h3>"Chennai": Pull a Rabbit from a Hat</h3>

Scenario: "Chennai": Pull a Rabbit from a Hat

Level: Hard

Type: Fix

Tags: docker   rabbitmq   realistic-interviews  

Description: There is a RabbitMQ (RMQ) cluster defined in a docker-compose.yml file.

Bring this system up and then run the producer.py script in such a way that is able to send messages to RMQ. In particular you have to send the message "hello-lwc".

- RMQ is a queuing system: messages are put in the queue with a "producer" and they are taken out from the other side by a "consumer". The queue name has to be the same for both.

- To send the message "hello-lwc": python3 ~/producer.py hello-lwc. Should return Message sent to RabbitMQ. "IncompatibleProtocolError" means RMQ is not working properly.

- To test consuming it: python3 ~/consumer.py, this will retrieve the next message from the queue and print it. Once everything is working send more than one message so there's at least one in the queue when the validation runs.

- Do not change the consumer.py and producer.py files; if you do the Check My Solution will fail.

Test: python3 ~/consumer.py returns hello-lwc

See /home/admin/agent/check.sh for the exact test.

Time to Solve: 30 minutes.