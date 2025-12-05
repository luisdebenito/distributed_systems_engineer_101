## 04/12/2025

My name is Luis, I studied Electronic and Automatic Industrial Engineering and I'm currently working as a software engineer. About to turn 30 in like 4 days.

 Feels weird, in one hand, super happy, because I've reached a level of life and job balance that 90% of people would wanna have, and I have plenty of time to do my stuff. In the other hand, I feel like I could do something better, something more, but FE + BE + Infra is not gonna give me that.

I have decided to start a joruney to become a distributed systems engineer, I think it is a niche field, there's not much people on it and I believe there is plenty of room for me. With the faster and growing AI world, instead of just complaining and watching my end get close, I'll take the chance to have one of the Educational AIs to be my professor and answer my doubts, recommend me books and papers I can dig in, and whatever you can imagine.

BTW: I'm writing this in a .md file, edited  using VSCodium in my Debian 13 OS running in a 2015 lenovo with Xfce desktop environment. I think it is clear that I'm an OG wannabe.


********

Packages needed to start the journey

 ```sudo apt install clang```



*********

I think the easiest way to start the journey is to create a simple TCP server that accepts client connections, with a C++ client that connects and sends messages. Let's first start by explaining wtf is a TCP server:


-  A TCP server is a program that listens for incoming connections from clients over the TCP protocol and exchanges data with them.

- TCP (Transmission Control Protocol) is a connection-oriented protocol. It ensures that data sent between a client and server is:
    - Delivered in order
    - Not lost or duplicated
    - Verified with checksums

- How a TCP server works:
    - Bind to an IP address and port.
    - Listen for incoming client connections.
    - Accept a client connection, which creates a dedicated channel for communication.
    - Send and receive data over that connection.
    - Close the connection when done.

- Example use cases:
    - Web servers (HTTP over TCP)
    - Chat servers
    - File transfer servers
    - Game servers

In short, a TCP server is the “host” that waits for clients to connect and reliably exchanges information with them.