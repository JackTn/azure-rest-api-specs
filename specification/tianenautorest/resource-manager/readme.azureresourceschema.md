## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

```yaml
batch:
  - tag: schema-tianenautorest-preview
```


### Tag: schema-2020-09-17 and azureresourceschema

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

```yaml
  output-folder: $(azureresourceschema-folder)/schemas

  # all the input files in this apiVersion
  input-file: 
    - Microsoft.TianenAutoRest/preview/2020-09-17/tianenautorest.json
```
