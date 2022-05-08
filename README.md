# CS542-Computer-Networking-I-Project-Report

Ping is a computer network application that checks whether a specific host can be reached via an IP network. It operates by sending ICMP "echo reply" packets to the target host and listening for responses. Ping calculates the round-trip duration, logs packet loss, and generates a statistical summary of the received echo back packets and saves the messages that are sent and received at the receiver side and the sender side.

Python Implementation:

In the python file we have both the sender and receiver which sends and receives the icmp messages using the local host
In the terminal run the code using sudo python3 filename.py
Two files will be created after successfully running the code which are reply.txt and request.txt.
“request.txt” consists of the data part which is getting added into the packet, the length of the sending packet and the packet which is requested. “reply.txt” consists of length of the received file packet, address from which it received the packet, the packet which is received, The icmp header of the received packet and the icmp packet type.
