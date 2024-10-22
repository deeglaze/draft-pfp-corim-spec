# TCG Draft document for Platform Firmware CoRIM profile

Whereas the PCClient PFP specifies events that a firmware should measure, this profile specifies how reference value providers for those events should represent their data.

## How to build locally

This specification can be built with the [TCG pandoc container](https://github.com/trustedcomputinggroup/pandoc).

```shell
docker pull ghcr.io/trustedcomputinggroup/pandoc:latest

./docker_run --pdf=spec.pdf spec.tcg
```
