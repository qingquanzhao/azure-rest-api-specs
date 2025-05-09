# LiftrBasic.SampleRP RP

> see https://aka.ms/autorest

This is the AutoRest configuration file for WeightsAndBiases service.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the WeightsAndBiases service.

```yaml
openapi-type: arm
openapi-subtype: rpaas
tag: package-2024-09-18
```
### Tag: package-2024-09-18

These settings apply only when `--tag=package-2024-09-18` is specified on the command line.

```yaml $(tag) == 'package-2024-09-18'
input-file:
  - Microsoft.WeightsAndBiases/stable/2024-09-18/openapi.json
```

### Tag: package-2024-09-18-preview

These settings apply only when `--tag=package-2024-09-18-preview` is specified on the command line.

```yaml $(tag) == 'package-2024-09-18-preview'
input-file:
  - Microsoft.WeightsAndBiases/preview/2024-09-18-preview/openapi.json
```
