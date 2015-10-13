#readme.txt

书名：
High Performance Browser Networking

作者：
Ilya Grigorik

[图书地址][bookurl]

###	翻译进度



*	Table of Contents
*	Foreword
*	Preface
*	+	About This Book
*	+	Conventions Used in This Book
*	+	Safari® Books Online
*	+	How to Contact Us
*	+	Content Updates
*	+	-	May 23, 2014
*	I. Networking 101
*	+	1. Primer on Latency and Bandwidth
*	+	-	Speed Is a Feature
*	+	-	The Many Components of Latency
*	+	-	Speed of Light and Propagation Latency
*	+	-	Last-Mile Latency
*	+	-	Bandwidth in Core Networks
*	+	-	Bandwidth at the Network Edge
*	+	-	Delivering Higher Bandwidth and Lower Latencies
*	+	2. Building Blocks of TCP
*	+	-	Three-Way Handshake
*	+	-	Congestion Avoidance and Control
*	+	-	*	Flow Control
*	+	-	*	Slow-Start
*	+	-	*	Congestion Avoidance
*	+	-	Bandwidth-Delay Product
*	+	-	Head-of-Line Blocking
*	+	-	Optimizing for TCP
*	+	-	*	Tuning Server Configuration
*	+	-	*	Tuning Application Behavior
*	+	-	*	Performance Checklist
*	+	3. Building Blocks of UDP
*	+	-	Null Protocol Services
*	+	-	UDP and Network Address Translators
*	+	-	*	Connection-State Timeouts
*	+	-	*	NAT Traversal
*	+	-	*	STUN, TURN, and ICE
*	+	-	Optimizing for UDP
*	+	4. Transport Layer Security (TLS)
*	+	-	Encryption, Authentication, and Integrity
*	+	-	TLS Handshake
*	+	-	*	RSA, Diffie-Hellman and Forward Secrecy
*	+	-	*	Application Layer Protocol Negotiation (ALPN)
*	+	-	*	Server Name Indication (SNI)
*	+	-	TLS Session Resumption
*	+	-	*	Session Identifiers
*	+	-	*	Session Tickets
*	+	-	Chain of Trust and Certificate Authorities
*	+	-	Certificate Revocation
*	+	-	*	Certificate Revocation List (CRL)
*	+	-	*	Online Certificate Status Protocol (OCSP)
*	+	-	TLS Record Protocol
*	+	-	Optimizing for TLS
*	+	-	*	Computational Costs
*	+	-	*	Early Termination
*	+	-	*	Session Caching and Stateless Resumption
*	+	-	*	TLS False Start
*	+	-	*	TLS Record Size
*	+	-	*	TLS Compression
*	+	-	*	Certificate-Chain Length
*	+	-	*	OCSP Stapling
*	+	-	*	HTTP Strict Transport Security (HSTS)
*	+	-	Performance Checklist
*	+	-	Testing and Verification
*	II. Performance of Wireless Networks
*	+	5. Introduction to Wireless Networks
*	+	-	Ubiquitous Connectivity
*	+	-	Types of Wireless Networks
*	+	-	Performance Fundamentals of Wireless Networks
*	+	-	*	Bandwidth
*	+	-	*	Signal Power
*	+	-	*	Modulation
*	+	-	Measuring Real-World Wireless Performance
*	+	6. WiFi
*	+	-	From Ethernet to a Wireless LAN
*	+	-	WiFi Standards and Features
*	+	-	Measuring and Optimizing WiFi Performance
*	+	-	*	Packet Loss in WiFi Networks
*	+	-	Optimizing for WiFi Networks
*	+	-	*	Leverage Unmetered Bandwidth
*	+	-	*	Adapt to Variable Bandwidth
*	+	-	*	Adapt to Variable Latency
*	+	7. Mobile Networks
*	+	-	Brief History of the G’s
*	+	-	*	First Data Services with 2G
*	+	-	*	3GPP and 3GPP2 Partnerships
*	+	-	*	Evolution of 3G Technologies
*	+	-	*	IMT-Advanced 4G Requirements
*	+	-	*	Long Term Evolution (LTE)
*	+	-	*	HSPA+ is Leading Worldwide 4G Adoption
*	+	-	*	Building for the Multigeneration Future
*	+	-	Device Features and Capabilities
*	+	-	*	User Equipment Category
*	+	-	Radio Resource Controller (RRC)
*	+	-	*	3G, 4G, and WiFi Power Requirements
*	+	-	*	LTE RRC State Machine
*	+	-	*	HSPA and HSPA+ (UMTS) RRC State Machine
*	+	-	*	EV-DO (CDMA) RRC State Machine
*	+	-	*	Inefficiency of Periodic Transfers
*	+	-	End-to-End Carrier Architecture
*	+	-	*	Radio Access Network (RAN)
*	+	-	*	Core Network (CN)
*	+	-	*	Backhaul Capacity and Latency
*	+	-	Packet Flow in a Mobile Network
*	+	-	*	Initiating a Request
*	+	-	*	Inbound Data Flow
*	+	-	Heterogeneous Networks (HetNets)
*	+	-	Real-World 3G, 4G, and WiFi Performance
*	+	8. Optimizing for Mobile Networks
*	+	-	Preserve Battery Power
*	+	-	Eliminate Periodic and Inefficient Data Transfers
*	+	-	*	Eliminate Unnecessary Application Keepalives
*	+	-	Anticipate Network Latency Overhead
*	+	-	*	Account for RRC State Transitions
*	+	-	*	Decouple User Interactions from Network Communication
*	+	-	Design for Variable Network Interface Availability
*	+	-	Burst Your Data and Return to Idle
*	+	-	Offload to WiFi Networks
*	+	-	Apply Protocol and Application Best Practices
*	III. HTTP
*	+	9. Brief History of HTTP
*	+	-	HTTP 0.9: The One-Line Protocol
*	+	-	HTTP/1.0: Rapid Growth and Informational RFC
*	+	-	HTTP/1.1: Internet Standard
*	+	-	HTTP/2: Improving Transport Performance
*	+	10. Primer on Web Performance
*	+	-	Hypertext, Web Pages, and Web Applications
*	+	-	Anatomy of a Modern Web Application
*	+	-	*	Speed, Performance, and Human Perception
*	+	-	*	Analyzing the Resource Waterfall
*	+	-	Performance Pillars: Computing, Rendering, Networking
*	+	-	*	More Bandwidth Doesn’t Matter (Much)
*	+	-	*	Latency as a Performance Bottleneck
*	+	-	Synthetic and Real-User Performance Measurement
*	+	-	Browser Optimization
*	+	11. HTTP/1.X
*	+	-	Benefits of Keepalive Connections
*	+	-	HTTP Pipelining
*	+	-	Using Multiple TCP Connections
*	+	-	Domain Sharding
*	+	-	Measuring and Controlling Protocol Overhead
*	+	-	Concatenation and Spriting
*	+	-	Resource Inlining
*	+	12. HTTP/2
*	+	-	Brief History of SPDY and HTTP/2
*	+	-	Design and Technical Goals
*	+	-	*	Binary Framing Layer
*	+	-	*	Streams, Messages, and Frames
*	+	-	*	Request and Response Multiplexing
*	+	-	*	Stream Prioritization
*	+	-	*	One Connection Per Origin
*	+	-	*	Flow Control
*	+	-	*	Server Push
*	+	-	*	Header Compression
*	+	-	*	Upgrading to HTTP/2
*	+	-	Brief Introduction to Binary Framing
*	+	-	*	Initiating a New Stream
*	+	-	*	Sending Application Data
*	+	-	*	Analyzing HTTP/2 Frame Data Flow
*	+	13. Optimizing Application Delivery
*	+	-	Optimizing Physical and Transport Layers
*	+	-	Evergreen Performance Best Practices
*	+	-	*	Cache Resources on the Client
*	+	-	*	Compress Transferred Data
*	+	-	*	Eliminate Unnecessary Request Bytes
*	+	-	*	Parallelize Request and Response Processing
*	+	-	Optimizing for HTTP/1.x
*	+	-	Optimizing for HTTP/2
*	+	-	*	Eliminate Domain Sharding
*	+	-	*	Minimize Concatenation and Image Spriting
*	+	-	*	Eliminate Roundtrips with Server Push
*	+	-	*	Test HTTP/2 Server Quality
*	IV. Browser APIs and Protocols
*	+	14. Primer on Browser Networking
*	+	-	Connection Management and Optimization
*	+	-	Network Security and Sandboxing
*	+	-	Resource and Client State Caching
*	+	-	Application APIs and Protocols
*	+	15. XMLHttpRequest
*	+	-	Brief History of XHR
*	+	-	Cross-Origin Resource Sharing (CORS)
*	+	-	Downloading Data with XHR
*	+	-	Uploading Data with XHR
*	+	-	Monitoring Download and Upload Progress
*	+	-	Streaming Data with XHR
*	+	-	Real-Time Notifications and Delivery
*	+	-	*	Polling with XHR
*	+	-	*	Long-Polling with XHR
*	+	-	XHR Use Cases and Performance
*	+	16. Server-Sent Events (SSE)
*	+	-	EventSource API
*	+	-	Event Stream Protocol
*	+	-	SSE Use Cases and Performance
*	+	17. WebSocket
*	+	-	WebSocket API
*	+	-	*	WS and WSS URL Schemes
*	+	-	*	Receiving Text and Binary Data
*	+	-	*	Sending Text and Binary Data
*	+	-	*	Subprotocol Negotiation
*	+	-	WebSocket Protocol
*	+	-	*	Binary Framing Layer
*	+	-	*	Protocol Extensions
*	+	-	*	HTTP Upgrade Negotiation
*	+	-	WebSocket Use Cases and Performance
*	+	-	*	Request and Response Streaming
*	+	-	*	Message Overhead
*	+	-	*	Data Efficiency and Compression
*	+	-	*	Custom Application Protocols
*	+	-	*	Deploying WebSocket Infrastructure
*	+	-	Performance Checklist
*	+	18. WebRTC
*	+	-	Standards and Development of WebRTC
*	+	-	Audio and Video Engines
*	+	-	*	Acquiring Audio and Video with getUserMedia
*	+	-	Real-Time Network Transports
*	+	-	*	Brief Introduction to RTCPeerConnection API
*	+	-	Establishing a Peer-to-Peer Connection
*	+	-	*	Signaling and Session Negotiation
*	+	-	*	Session Description Protocol (SDP)
*	+	-	*	Interactive Connectivity Establishment (ICE)
*	+	-	*	Incremental Provisioning (Trickle ICE)
*	+	-	*	Tracking ICE Gathering and Connectivity Status
*	+	-	*	Putting It All Together
*	+	-	Delivering Media and Application Data
*	+	-	*	Secure Communication with DTLS
*	+	-	*	Delivering Media with SRTP and SRTCP
*	+	-	*	Delivering application data with SCTP
*	+	-	DataChannel
*	+	-	*	Setup and Negotiation
*	+	-	*	Configuring Message Order and Reliability
*	+	-	*	Partially Reliable Delivery and Message Size
*	+	-	WebRTC Use Cases and Performance
*	+	-	*	Audio, Video, and Data Streaming
*	+	-	*	Multiparty Architectures
*	+	-	*	Infrastructure and Capacity Planning
*	+	-	*	Data Efficiency and Compression
*	+	-	Performance Checklist
*	Index
---

[bookurl]:	http://chimera.labs.oreilly.com/books/1230000000545
