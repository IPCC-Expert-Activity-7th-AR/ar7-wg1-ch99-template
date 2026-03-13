# Contributing

This repository follows the AR7 WGI GitHub organization guidance for repository structure, workflows, and data/metadata practices.

- **Repository structure:** Figure folders must match the convention described in the root [README](README.md) and are validated by the [`.github/workflows/validate.yml`](.github/workflows/validate.yml) workflow on push to `main`.
- **Data and metadata:** Use the `data/` layout and YAML metadata templates as described in [data/README.md](data/README.md) and in each figure’s `data/` subfolders. Do not commit large datasets; document access and provenance in metadata only.
- **Licensing:** Code and documentation in this repository are under the [Apache License 2.0](LICENSE). Each figure folder also contains its own LICENSE.

For organization-level contribution and permission guidelines (e.g. branch protection, roles, security reporting), refer to the AR7 WGI GitHub organization documentation when available.
