## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

```yaml
batch:
  - tag: schema-tianenalertsmanagement-2020-09-30
```


### Tag: schema-2020-09-30 and azureresourceschema

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

```yaml
  output-folder: $(azureresourceschema-folder)/schemas

  # all the input files in this apiVersion
  input-file: 
    - Microsoft.TianenAlertsManagement/preview/2020-09-30/tianenalertsmanagement.json
```
