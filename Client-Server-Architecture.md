<div align=center>
<h3>2</h3>
  <h1>Client Server Architecture</h1>
</div>

## Client Server Architecture

- The Client-Server Architecture tells you about Servers, Connection between a client and the server and how it takes place.
- The client-server network is usually scaled large across countries and even continents.
- Client send request and server sent a response.

## Servers

- Servers are the points where a client connects to have a connection for getting/providing a service, to do some task, etc.
- The servers have high upload speed because of what they need to do and their nature.
- The servers of big companies are distributed and they usually do not have only a single server.
- The collection of servers is called Data Centers.

## Ping
- It measures the round trip time for messages send from originating host to destination computers and they are acord back.The entire time is known ans Ping time.
  

## Client

- Client is us, who connects to the server for doing a task or for getting a service.
- Clients have high download speed (as compared to the upload speed).
- When `Client A` wants to connect to `Client B`, then this connection takes place only through the server, I.E.: Gaming.



# Peer to Peer Communication

- The devices gets connected to one another and there is no large server in this architecture.
- This can be scaled very rapidly and is a decentralized network.
- This network lets a device to communicate with other device(s) directly.
- Peer to peer networks are commonly small scale.
- Peer to peer networking can be more effective than client server networking because every computer on the network is given equal responsibility to communicate with each other.
- In peer to peer network every single computer can termed as server or client.

# Devices

- These are some networking devices that we should atleast have an idea of, when learning networking and how a connection is established between devices and what happens in between.


## Repeater

- A repeater operates at the physical layer.
- This device takes the network signal and sends it again in the desired direction before the signal becomes weak over the same network.
- These don't amplify the network but they regenerate the detected network with the same strength.
- It's a 2 port device.

## Hub

- This is a multiport repeater.
- This cannot filter data and so the data is sent to all connected devices.
- The collision domain of all hosts through Hub remains one.
- They do not have the intelligence to find out best path for data packets which leads to inefficenies and wastage.
- There are two types of hub:
                        - Active Hub
                        - Passive Hub

### Active Hub

- This has its own power supply and can clean, boost and relay the signal along the given network.
- It serves both as a repeater as well as wiring center.
- Used to extend maximum distance between two nodes.


### Passive Hub

- These are the hubs which collect wiring from nodes and  power supply from active hub.
- These hubs relay signals onto the network without cleaning and boosting them.
- Can't be used to extend maximum distance between two nodes.


## Bridge

- This operates at Data Link Layer.
- It is a repeater.
- It filters content by reading MAC Addresses of source and destination.
- It is also used for interconnecting two LANs working on the same protocol.
- It has single input and single output port.

## Types of Bridge
 **Transparent Bridge-**

- In this the stations are completely unaware of the presence of bridge.
- These bridges makes use of two processes i.e bridge forwording and bridge learning
  
**Source Routing Bridge**
- In this, routing operation is performed by source station and the frame specifies which route to follow.
  

## Switch

- This is a multi port bridge with a buffer and a design that can boost efficiency and performence.
- Large number of ports imply less traffic.
- It is a data link layer device.
- Error checking is done before forwording data, that makes it very efficient as it does not forword packets that have errors and only good packets selectively to correct port only. 

## Router

- This operates at Network layer.
- Connects LANs and WANs.
- This has a dynamic routing table.

## Gateway

- It is a passage to connect two networks together that may work upon different networking models.
- Messenger agents that take data from one system, interpret it and transfer it to another system.
- Gateway are also called protocol converters and can operate at any network layer.

## Brouter
- Bridge and router combined.
- This can work either at Networking Layer or at Data Link layer.
