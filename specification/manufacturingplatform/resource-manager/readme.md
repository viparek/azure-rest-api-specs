# manufacturingplatform

> see https://aka.ms/autorest

This is the AutoRest configuration file for manufacturingplatform.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the manufacturingplatform.

```yaml
openapi-type: arm
openapi-subtype: providerHub
tag: package-2025-03-01
```

### Tag: package-2025-03-01

These settings apply only when `--tag=package-2025-03-01` is specified on the command line.

```yaml $(tag) == 'package-2025-03-01'
input-file:
  - Microsoft.ManufacturingPlatform/stable/2025-03-01/manufacturingplatform.json
suppressions:
  - code: AvoidAnonymousTypes
    from: manufacturingplatform.json
    reason: Swagger LintDiff false positive 
```
---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

```yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python-track2
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-js
  - repo: azure-resource-manager-schemas
  - repo: azure-cli-extensions
  - repo: azure-powershell
```
## Az

See configuration in [readme.az.md](./readme.az.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)
