## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

```yaml
batch:
  - tag: schema-tianenautomation-2020-09-22
```


### Tag: schema-2020-09-22 and azureresourceschema

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

```yaml
  output-folder: $(azureresourceschema-folder)/schemas

  # all the input files in this apiVersion
  input-file: 
    - Microsoft.TianenAutomation/preview/2020-09-22/tianenautomation.json
```
