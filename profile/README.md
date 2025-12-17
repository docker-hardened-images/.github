<img alt="dhi-banner" src="https://github.com/user-attachments/assets/fc0ca203-3f25-4ae5-aa8e-e3918bbcc31f" />

# Docker Hardened Images

Docker Hardened Images (DHI) are built to meet the highest security and compliance standards. They provide a trusted foundation for containerized workloads by incorporating security best practices from the start.

DHI images are available under [Apache License 2.0](https://github.com/docker-hardened-images/catalog/blob/main/LICENSE.txt). 

> [!IMPORTANT]
> Read the announcement blog post: [A Safer Container Ecosystem with Docker: Free Docker Hardened Images](https://www.docker.com/blog/docker-hardened-images-for-every-developer/).

## 🎯 Overview

Docker Hardened Images provides a curated collection of container images built with security and minimalism as core principles. Each image is:

- **Security-focused**: Published with zero-known CVEs and hardened configurations
- **Transparent**: Complete Software Bill of Materials (SBOM) and VEX metadata
- **Verified**: Signed provenance for supply chain security
- **Production-ready**: Configured with best practices for enterprise deployments
- **Continuously updated**: Regularly maintained with the latest security patches

## 📚 Repositories

- **[Catalog](https://github.com/docker-hardened-images/catalog)**: Image, Helm chart, and package definitions
- **[Discussions](https://github.com/orgs/docker-hardened-images/discussions)**: Community forum and product discussions
- **[Advisories](https://github.com/docker-hardened-images/advisories)**: Security advisories and vulnerability information
- **[Changelog](https://github.com/docker-hardened-images/log)**: Release notes and update history
- **[Keyring](https://github.com/docker-hardened-images/keyring)**: Signing keys and verification tools

## 🚀 Getting Started

Pre-built images are available:

```bash
docker login dhi.io

docker pull dhi.io/node:24-debian13
docker pull dhi.io/python:3.12-alpine3.22
docker pull dhi.io/postgres:17-debian13
```

The entire catalog of images and charts is available at https://dhi.io.

## 🔗 Links

- **Docker Hardened Images**: [docker.com/products/hardened-images](https://docker.com/products/hardened-images/)
- **Product Catalog**: [dhi.io](https://dhi.io)
- **Blog**: [Introducing Docker Hardened Images](https://www.docker.com/blog/introducing-docker-hardened-images/)
- **Commercial Support**: [docker.com/support](https://docker.com/support/)

---

**Docker Hardened Images** - Building secure containers, together.
