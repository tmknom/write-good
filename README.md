# write-good

[![CircleCI](https://circleci.com/gh/tmknom/write-good.svg?style=svg)](https://circleci.com/gh/tmknom/write-good)
[![Docker Build Status](https://img.shields.io/docker/build/tmknom/write-good.svg)](https://hub.docker.com/r/tmknom/write-good/builds/)
[![Docker Automated build](https://img.shields.io/docker/automated/tmknom/write-good.svg)](https://hub.docker.com/r/tmknom/write-good/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/tmknom/write-good.svg)](https://microbadger.com/images/tmknom/write-good)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/tmknom/write-good.svg)](https://microbadger.com/images/tmknom/write-good)
[![License](https://img.shields.io/github/license/tmknom/write-good.svg)](https://opensource.org/licenses/Apache-2.0)

Dockerfile template.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/write-good/master/install | sh -s example
cd example
```

## Makefile targets

```text
build                          Build docker image
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
```

## Development

### Installation

```shell
git clone git@github.com:tmknom/write-good.git
cd write-good
make install
```

### Deployment

Automatically deployed by "[DockerHub Automated Build](https://docs.docker.com/docker-hub/builds/)" after merge.

### Deployment Pipeline

1. GitHub - Version Control System
   - <https://github.com/tmknom/write-good>
2. CircleCI - Continuous Integration
   - <https://circleci.com/gh/tmknom/write-good>
3. Docker Hub - Docker Registry
   - <https://hub.docker.com/r/tmknom/write-good/>
4. MicroBadger - Docker Inspection
   - <https://microbadger.com/images/tmknom/write-good>

## License

Apache 2 Licensed. See LICENSE for full details.
