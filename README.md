# Hi, I'm Younghun 👋

Backend Engineer interested in **Go, distributed systems, and observability**.

I enjoy building backend systems, finding bottlenecks through measurement, and improving them with a focus on reliability.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/younghun-hwang-85161525a)
[![Velog](https://img.shields.io/badge/Velog-20C997?logo=velog\&logoColor=white)](https://velog.io/@younghun/posts)

## Featured Project

### [Go Chat MSA](https://github.com/happyhun/go-chat-msa)

A distributed chat backend built with **Go, gRPC, WebSocket, and Kubernetes**.

* Designed WebSocket routing with **consistent hashing** for horizontal scaling
* Preserved message ordering during instance ownership changes
* Separated real-time fan-out from persistence with **asynchronous batch writes**
* Built observability with **OpenTelemetry, Prometheus, Loki, Tempo, and Pyroscope**
* Load tested with **10,000 concurrent WebSocket connections**
* Reached approximately **2K msg/s ingress and 200K msg/s fan-out**
* Improved bottlenecks using **k6 load testing, metrics, traces, and profiling**

→ See the repository for architecture, performance reports, and design trade-offs.

## Open Source

* **Buf** — Reported and reproduced a **Buf Language Server crash** triggered by files without a trailing newline. The report led to an upstream fix: [issue #676](https://github.com/bufbuild/vscode-buf/issues/676) → [PR #4693](https://github.com/bufbuild/buf/pull/4693)

## Currently Exploring

* Go open-source contribution
* Distributed backend architecture
* High-throughput messaging and concurrency
* Performance engineering and load testing
* Observability internals
