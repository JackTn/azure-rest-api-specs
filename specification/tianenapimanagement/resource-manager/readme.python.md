## Python

These settings apply only when `--python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

```yaml $(python)
python-mode: create
python:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  payload-flattening-threshold: 2
  namespace: Microsoft.TianenApiManagement
  package-name: azure-mgmt-tianenapimanagement
  package-version: 2020-09-27
  clear-output-folder: true
```

These settings apply only when `--track2` is specified on the command line.

```yaml $(python)
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  package-name: azure-mgmt-tianenapimanagement
  no-namespace-folders: true
  package-version: 2020-09-27
```

```yaml $(python)
python:
  no-namespace-folders: true
  output-folder: $(python-sdks-folder)/tianenapimanagement/azure-mgmt-tianenapimanagement
```

```yaml $(python)
python:
  basic-setup-py: true
  output-folder: $(python-sdks-folder)/tianenapimanagement/azure-mgmt-tianenapimanagement
```
