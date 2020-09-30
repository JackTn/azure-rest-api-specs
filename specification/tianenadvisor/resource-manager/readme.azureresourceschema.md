## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

```yaml
batch:
  - tag: schema-tianenadvisor-2020-09-22
```


### Tag: schema-2020-09-22 and azureresourceschema

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

```yaml
  output-folder: $(azureresourceschema-folder)/schemas

  # all the input files in this apiVersion
  input-file: 
    - Microsoft.TianenAdvisor/preview/2020-09-22/tianenadvisor.json
```
