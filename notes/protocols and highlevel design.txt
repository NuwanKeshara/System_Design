1) Transport Layer Protocols:
- TCP
- UDP

- QUIC


2) Application Layer Protocols
- HTTP/HTTPS (TCP)
- WebSockets (initially begins with http then move to websocket) (TCP) - chat/ messaging/ updates
- WebRTC (UDP) - video/ audio

- FTP (TCP)
- SSH (TCP)
- SMTP (TCP)


3) High Level Designs (Not Protocols) on top of Application Layer Protocols
- REST (HTTP) - simple CRUDs
- SOAP (HTTP) - heavy/ enterprised level apps (banks)
- GraphQL (HTTP/ WebSockets) - data heavy apps
- WebHooks (HTTP) - server push
- gRPC (HTTP/2) - microservices/ streaming (websockets < grpc but fails in browser based and also websockets works well with pub/sub, chats)



       |-- Versioning: HTTP/1.1, HTTP/2, HTTP/3
HTTP --
       |-- Security: HTTP (no TLS, plain text), 
                     HTTPS (with TLS)



HTTP/1.1 -- common: HTTP
         -- rare: HTTPS


HTTP/2   -- common: HTTPS
         -- rare: HTTP


HTTP/3   -- always: HTTPS