HTTP/0.9:

1.  Single-line requests with the GET method followed by the resource path.

HTTP/1.0:

1.  Versioning information in each request.
2.  Status code line in response, allowing browsers to recognize the success or failure of a request.
3.  Introduction of [[HTTP]] headers for both requests and responses, making the protocol more flexible and extensible.
4.  Transmission of documents other than plain HTML files, thanks to the Content-Type header.

HTTP/1.1:

1.  Reusing connections, saving time by reducing the need to open multiple connections.
2.  Pipelining, allowing a second request to be sent before the answer to the first one was fully transmitted, reducing latency.
3.  Support for chunked responses.
4.  Additional cache control mechanisms.
5.  Content negotiation, including language, encoding, and type.
6.  Hosting different domains from the same IP address with the Host header, enabling server collocation.

HTTP/2:

1.  Binary protocol instead of a text-based protocol, allowing for improved optimization techniques.
2.  Multiplexed protocol, enabling parallel requests over the same connection.
3.  Header compression to reduce duplication and overhead of data transmitted.
4.  Server push, allowing the server to populate data in the client cache.

HTTP/3:

1.  Usage of QUIC instead of TCP for the transport layer, providing much lower latency.
2.  Independent packet loss detection and retransmission for each stream, preventing blocking of all streams in case of an error.