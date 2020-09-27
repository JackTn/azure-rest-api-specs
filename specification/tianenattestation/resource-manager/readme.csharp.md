## C

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-sdks-folder=<path to "SDKs" directory of your azure-sdk-for-net clone>`.

```yaml $(csharp)
csharp:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  payload-flattening-threshold: 1
  clear-output-folder: true
  client-side-validation: false
  namespace: Microsoft.TianenAttestation
  output-folder: $(csharp-sdks-folder)/tianenattestation/management/Microsoft.TianenAttestation/GeneratedProtocol
  test: this is a test file to confirm what is the placeholder meaning
  resourceProviderName: Microsoft.TianenAttestation
  serviceName: tianenattestation
  serviceType: resource-manager
  version: 2020-09-27
  releaseState: preview
  openAPiType: arm
```
