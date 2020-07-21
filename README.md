### Real-Time-Multiple-User-Messaging-Server

---

1. CLI host-client connection server created in C. 
2. Used FIFO(Pipe-like structure) for data transfer between processes and Poll for efficient message update from FIFO.
3. Utilized multiple threads to simulate clients while processing incoming message and sent message at the same time.
