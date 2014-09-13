SkyDNS Dockerfile for Joukou
============================
[![Circle CI](https://circleci.com/gh/joukou/joukou-docker-skydns/tree/develop.png?style=badge&circle-token=0c23a4ca1e71f52e5c55cfd3e25e1658957f4da6)](https://circleci.com/gh/joukou/joukou-docker-skydns/tree/develop) [![Docker Repository on Quay.io](https://quay.io/repository/joukou/skydns/status?token=7359ce06-427d-4d66-9943-9e0aa6342a47 "Docker Repository on Quay.io")](https://quay.io/repository/joukou/skydns) [![Apache 2.0](http://img.shields.io/badge/License-Apache%202.0-brightgreen.svg)](#license) [![Stories in Ready](https://badge.waffle.io/joukou/joukou-docker-skydns.png?label=ready&title=Ready)](http://waffle.io/joukou/joukou-docker-skydns) [![IRC](http://img.shields.io/badge/IRC-%23joukou-blue.svg)](http://webchat.freenode.net/?channels=joukou)

[SkyDNS](https://github.com/skynetservices/skydns) Dockerfile for
[Joukou](https://joukou.com).

## Usage

Executed via [Joukou Fleet Units](https://github.com/joukou/joukou-fleet).

## Base Image

See [`quay.io/joukou/golang`](https://github.com/joukou/joukou-docker-golang).

## Exposed Ports

| Port      | Purpose                               |
| --------- | ------------------------------------- |
| 53        | DNS                                   |

## Metrics

[![Throughput Graph](https://graphs.waffle.io/joukou/joukou-docker-skydns/throughput.svg)](https://waffle.io/joukou/joukou-docker-skydns/metrics)

## Contributors

* [Isaac Johnston](https://github.com/superstructor) ([Joukou Ltd](https://joukou.com))

## License

Copyright &copy; 2014 Joukou Ltd.

SkyDNS Dockerfile for Joukou is under the Apache 2.0 license. See the
[LICENSE](LICENSE) file for details.
