***

**Fork details**

This branch is a fork of [quic-go/http3] with minor API changes to use [quic-api] instead of the concrete [quic-go] data
structures as input.

The code and functionality are otherwise the same as mainline [quic-go/http3] and 100% compatible with [quic-go].

See [tlsproxy#211](https://github.com/c2FmZQ/tlsproxy/issues/211) for context and motivation.

[quic-go/http3]: https://github.com/quic-go/quic-go/tree/master/http3
[quic-api]: https://pkg.go.dev/github.com/c2FmZQ/quic-api
[quic-go]: https://pkg.go.dev/github.com/quic-go/quic-go

***

# HTTP/3

[![Documentation](https://img.shields.io/badge/docs-quic--go.net-red?style=flat)](https://quic-go.net/docs/)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/quic-go/quic-go/http3)](https://pkg.go.dev/github.com/quic-go/quic-go/http3)

This package implements HTTP/3 ([RFC 9114](https://datatracker.ietf.org/doc/html/rfc9114)), including QPACK ([RFC 9204](https://datatracker.ietf.org/doc/html/rfc9204)) and HTTP Datagrams ([RFC 9297](https://datatracker.ietf.org/doc/html/rfc9297)).
It aims to provide feature parity with the standard library's HTTP/1.1 and HTTP/2 implementation.

Detailed documentation can be found on [quic-go.net](https://quic-go.net/docs/).
