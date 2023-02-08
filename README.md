<div align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
	<p>
		A curated list of awesome <a href="https://en.wikipedia.org/wiki/QUIC">QUIC</a> and <a href="https://en.wikipedia.org/wiki/HTTP/3">HTTP/3</a> resources.
	</p>
</div>



## Contents

- [Learn](#learn)
- [Implementations](#implementations)
- [Tools](#tools)
- [Contributing](#contributing)


## Learn

- [IETF QUIC Working Group](https://quicwg.org/)
- [A Comprehensive Guide To HTTP/3 And QUIC](https://www.debugbear.com/blog/http3-quic-protocol-guide) - In-depth explanation of HTTP/3
- [HTTP/3 explained](https://http3-explained.haxx.se/) - A friendly and collaborative description of the HTTP/3 and QUIC protocols


## Implementations

*C*
 
 - [lsquic](https://github.com/litespeedtech/lsquic) - LiteSpeed QUIC and HTTP/3 library
 - [msquic](https://github.com/microsoft/msquic) - Microsoft's general purpose (cross-platform) QUIC implementation
 - [nghttp3](https://github.com/ngtcp2/nghttp3) -  HTTP/3 library written in C
 - [nginx-quic](https://hg.nginx.org/nginx-quic/) - Nginx QUIC and HTTP/3 server implementation
 - [ngtcp2](https://github.com/ngtcp2/ngtcp2) - ngtcp2 project is an effort to implement IETF QUIC protocol 
 - [picoquic](https://github.com/private-octopus/picoquic) - A small(ish) implementation of QUIC in C
 - [quant](https://github.com/NTAP/quant) - QUIC Userspace Accelerated Network Transfers
 - [quicly](https://github.com/h2o/quicly) - A modular QUIC stack designed primarily for H2O HTTP server
 - [xquic](https://github.com/alibaba/xquic) - Alibaba's cross-platform QUIC and HTTP/3 protocol implementation

*C++*

 - [QUICHE](https://github.com/google/quiche) - Google's implementation of QUIC, HTTP/2, HTTP/3, and related protocols and tools
 - [mvfst](https://github.com/facebookincubator/mvfst) - Facebook's QUIC implementation (pronounced move fast)
 - [proxygen](https://github.com/facebook/proxygen) - HTTP/3 mapping over QUIC and QPACK, with mvfst as the transport

*Go*

 - [quic-go](https://github.com/lucas-clemente/quic-go/) -  A QUIC implementation in pure go

*Haskell*

 - [quic](https://github.com/kazu-yamamoto/quic) - QUIC protocol implementation based on Haskell lightweight threads

*Java*

 - [flupke](https://bitbucket.org/pjtr/flupke/src/master/) - HTTP3 client build on top of Kwik
 - [kwik](https://bitbucket.org/pjtr/kwik/) - QUIC client (and client library) implementation

*Python*

 - [aioquic](https://github.com/aiortc/aioquic) - Python library for QUIC & HTTP/3

*Rust*

 - [neqo](https://github.com/mozilla/neqo) - Mozilla's QUIC and HTTP/3 implementation
 - [quiche](https://github.com/cloudflare/quiche) - Cloudfare's QUIC implementation
 - [quinn](https://github.com/quinn-rs/quinn) - Async-friendly QUIC implementation in Rust
 - [s2n-quic](https://github.com/aws/s2n-quic) - AWS Rust implementation of the QUIC protocol 


## Tools

*QUIC support*

- [Can I use HTTP/3](https://caniuse.com/http3) - Up-to-date browser support tables for HTTP/3 support
- [QUIC Interop Runner](https://interop.seemann.io/) - Interop status of various QUIC client and server implementations
- https://cloudflare-quic.com/ 
- https://quic.nginx.org/

*Does my website support QUIC?*

- [HTTP/3 Check](https://www.http3check.net/) - Test whether a server supports QUIC and the HTTP/3 semantics
- [Geekflare's HTTP/3 Test](https://geekflare.com/tools/http3-test) - Test if H3/QUIC is enabled on your website
- [Firefox addon - HTTP version indicator](https://addons.mozilla.org/en-US/firefox/addon/http2-indicator/)

*Other tools*

- [qvis](https://github.com/quiclog/qvis) - A set of QUIC and HTTP/3 visualization tools
- [curl-http3 Docker image](https://hub.docker.com/r/rmarx/curl-http3) - Docker image of cURL with full H3 support for no-nonsense testing



## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
