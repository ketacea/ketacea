# [KetaOps](https://github.com/ketaops)

## Highlighted Features

- **Out-of-the-box**
    - Supports multiple deployment methods: ansible, docker, helm.
- **Unified Query Language**
    - Supports log、metric、trace query with spl（search process language）
    - Supports agent streaming transformer with spl
- **High Performance**
    - Friendly to memory and cpu、simd-based vectorized computing engine
- **One Agent**
    - 300+ datasource including intra、kubernetes、middleware、logs、tracing、database consumer etc
## Getting Started

The following resources are available:

- [Architecture](docs/architecture.md): How the ketaops can be deployed
- [Monitoring](docs/monitoring.md): How to ensure the ketaops is healthy
- [Troubleshooting](docs/troubleshooting.md): How to resolve common issues

This distribution is supported on and packaged for a variety of platforms including:
- Docker:
  - [Docker Compose](https://github.com/ketaops/docker-compose)
- Kubernetes
  - [Helm (recommended)](https://github.com/ketaops/helm-charts)
- Linux
  - Configuration management (recommended for multi-host production environments)
    - [Ansible](https://github.com/ketaops/ansible)