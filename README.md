# ymuse

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/ymuse)
[![General Workflow](https://github.com/rolehippie/ymuse/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/ymuse/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/ymuse/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/ymuse/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/ymuse/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/ymuse/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/ymuse)](https://github.com/rolehippie/ymuse/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.ymuse-blue)](https://galaxy.ansible.com/rolehippie/ymuse)

> [!IMPORTANT]
> This role have been archived because of the lack of maintenance and because
> we are not actively using it anymore. If you are using this role feel free
> to fork and maintain it on your own. Maybe we will unarchive this repository
> in the future at some point, maybe not... Who knows...

Ansible role to install ymuse music player.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [ymuse_arch](#ymuse_arch)
  - [ymuse_package](#ymuse_package)
  - [ymuse_version](#ymuse_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### ymuse_arch

Architecture for the package

#### Default value

```YAML
ymuse_arch: amd64
```

### ymuse_package

Download URL for the package to install

#### Default value

```YAML
ymuse_package: https://github.com/yktoo/ymuse/releases/download/v{{ ymuse_version
  }}/ymuse_{{ ymuse_version }}_linux_{{ ymuse_arch }}.deb
```

### ymuse_version

Version for the package

#### Default value

```YAML
ymuse_version: 0.21
```

## Discovered Tags

**_ymuse_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
