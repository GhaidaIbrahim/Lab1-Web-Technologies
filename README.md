# Web Technologies Lab 1
**Name:** غيداء الحربي
**Lab Number:** 1

## Summary of Work
In this lab, I used Wireshark to capture and analyze different network protocols (HTTP, TCP, and UDP). The goal was to understand how data is packaged and transmitted across the network.
---
### Personal Notes & Key Takeaways:
* **HTTP:** Analyzed the basic Request/Response cycle (GET and 200 OK) for an unencrypted website.
* **TCP:** Focused on the connection lifecycle:
  - Started with the 3-way handshake (SYN, SYN-ACK, ACK).
  - Followed the TCP stream to see the actual data exchange.
  - Observed how the session closes with the [FIN] flag.
* **UDP:** Noted the simplicity of UDP through DNS queries. Unlike TCP, it’s much faster because it doesn't require a connection setup.
* **Comparison:** TCP is reliable and ensures data arrives in order, while UDP is all about speed and low overhead.

---
## Lab Files
* **Screenshots:** Documentation of all captured packets and handshakes for each step 
* **Final Tables:** Comparison of protocol performance and use cases.
