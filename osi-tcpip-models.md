# TCP/IP & OSI Model

## OSI Model (7 Layers)
1. Physical - Cables, signals, Wi-Fi. Basically how raw data travels.
2. Data Link - Uses MAC address, handles local delivery and error checking (switches work here)
3. Network - Deals with IP address and routing (routers decide the path here)
4. Transport - Makes sure data reaches properly using TCP/UDP (reliable or fast delivery)
5. Session - Keeps the connection alive between devices (start, maintain, end)
6. Presentation - Converts data format, handles encryption/decryption, compression
7. Application - What we actually use like browser, email, HTTP, FTP

Simple idea: When you open a website, your data travels through all these layers one by one.


## TCP/IP Model (4 Layers)
1. Link - Combines physical + data link (hardware + local communication)
2. Internet - Handles IP addressing and routing between networks
3. Transport - TCP/UDP handles communication between devices
4. Application - All user-level services like HTTP, DNS, FTP

This is what the real internet actually follows.

---

## OSI vs TCP/IP
- OSI is mainly for learning and understanding concepts
- TCP/IP is what is actually used in real-world internet
- OSI has 7 layers, TCP/IP has 4 layers
- TCP/IP basically compresses OSI layers into practical groups


## Key Understanding
- Every online action (WhatsApp message, YouTube video, browsing) is just data moving through layers
- You don’t see it, but behind the scenes data goes from top layer → bottom layer (sender)
- Then again bottom → top (receiver)