---
Aliases: UDP, User Datagram Protocol
---
#UDP

UDP (User Datagram Protocol) is a connectionless and unreliable networking protocol that operates at the transport layer of the [[OSI]] model. It provides a simple and lightweight mechanism for sending datagrams from one device to another over an IP network. Here are some key characteristics and features of UDP:

1. Connectionless: Unlike TCP (Transmission Control Protocol), which establishes a reliable connection between two devices before data transfer, UDP does not establish any connection. It simply sends data packets called datagrams without prior communication or acknowledgment.

2. Unreliable: UDP does not guarantee delivery, ordering, or error-checking of data packets. It assumes that the underlying network is reliable enough to handle any loss or corruption of packets.

3. Low overhead: Due to its simplicity, UDP has lower overhead than TCP, making it faster and more efficient for certain types of applications where reliability is not crucial.

4. No congestion control: Unlike TCP, which performs congestion control to prevent network congestion, UDP does not have built-in congestion control mechanisms. This can result in potential network congestion if too many packets are sent simultaneously.

5. Broadcast and multicast support: UDP supports broadcasting and multicasting of data packets, allowing a single sender to transmit data to multiple recipients simultaneously.

6. Real-time applications: UDP is commonly used in real-time applications such as video streaming, voice over IP (VoIP), online gaming, and live video conferencing due to its low latency and fast transmission speed.

7. Datagram boundaries preservation: UDP preserves the boundaries of individual datagrams during transmission, meaning the receiver will receive each datagram intact without having to reconstruct the data stream.

8. Port numbers: Similar to TCP, UDP uses port numbers to identify different services or applications running on devices within an IP network. These port numbers help in routing incoming datagrams to their respective destinations.

Despite its lack of reliability compared to TCP, UDP remains popular for specific use cases where speed and low latency are more important than guaranteed delivery. It is ideal for applications that can tolerate some packet loss or can handle error recovery at the application layer.