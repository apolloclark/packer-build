# packer-build

Generic Packer project, for building Docker images, using Ansible, and Serverspec.
The intent is to clone this as a submodule project into other projects

## Requirements

- [Packer](https://packer.io/)
- [Ansible](https://www.ansible.com/)
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Serverspec](https://serverspec.org/): gem install serverspec
- [docker-api](https://github.com/swipely/docker-api/releases): gem install docker-api

## Install

```shell
git submodule add https://github.com/apolloclark/packer-build
```
