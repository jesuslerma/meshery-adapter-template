<a href="https://layer5.io/meshery"><img align="right" src="https://raw.githubusercontent.com/layer5io/meshery/master/ui/static/img/meshery-logo/meshery-logo-light-text.png"  width="25%" /></a>

[![Docker Pulls](https://img.shields.io/docker/pulls/layer5/meshery.svg)](https://hub.docker.com/r/layer5/meshery)
[![Go Report Card](https://goreportcard.com/badge/github.com/layer5io/meshery)](https://goreportcard.com/report/github.com/layer5io/meshery)
[![Build Status](https://github.com/layer5io/meshery/workflows/Meshery/badge.svg)](https://github.com/layer5io/meshery/actions)
[![GitHub](https://img.shields.io/github/license/layer5io/meshery.svg)](LICENSE)
[![GitHub issues by-label](https://img.shields.io/github/issues/layer5io/meshery/help%20wanted.svg)](https://github.com/layer5io/meshery/issues?q=is%3Aopen+is%3Aissue+label%3A"help+wanted")
[![Website](https://img.shields.io/website/https/layer5.io/meshery.svg)](https://layer5.io/meshery/)
[![Twitter Follow](https://img.shields.io/twitter/follow/layer5.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=mesheryio)
[![Slack](http://slack.layer5.io/badge.svg)](http://slack.layer5.io)

# Setup
To setup the adapter from the template, we have a make command, which ONLY works on a Mac at the moment.

The template command is:
```
make setup-adapter ADAPTER=<NAME OF THE ADAPTER> PORT=<PORT TO USE> GO_VERSION=<GO VERSION>
```

Example:
For an adapter with name `adapter`, port `12121` and Go version `1.13.4`, the command will be:
```
make setup-adapter ADAPTER=adapter PORT=12121 GO_VERSION=1.13.4
```

__Please Note__: Do not include "meshery-" in the adapter name.

# meshery-\<adapter>
Meshery adapter for \<adapter>

## [Meshery](https://layer5.io/meshery)

A service mesh playground to faciliate learning about functionality and performance of different service meshes. Meshery incorporates the collection and display of metrics from applications running in the playground.

## Contributing
Please do! Contributions, updates, [discrepancy reports](/../../issues) and [pull requests](/../../pulls) are welcome. This project is community-built and welcomes collaboration. Contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

Not sure where to start? See the [newcomers welcome guide](https://docs.google.com/document/d/14Fofs9BysojB5igihXBI_SsFWoSUu-QRsGnnFqUvR0M/edit) for how, where and why to contribute. Or grab an open issue with the [help-wanted label](../../labels/help%20wanted) and jump in.

## License

This repository and site are available as open source under the terms of the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).

#### About Layer5
[Layer5.io](https://layer5.io) is a service mesh community, serving as a repository for information pertaining to the surrounding technology ecosystem (service meshes, api gateways, edge proxies, ingress and egress controllers) of microservice management in cloud native environments.
