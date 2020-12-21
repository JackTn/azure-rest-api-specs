## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

``` yaml $(azureresourceschema) && $(multiapi)
batch:
  - tag: schema-tianenappplatform-2020-11-26.1.2
  
```

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

### Tag: schema-tianenappplatform-2020-11-26.1.2 and azureresourceschema

``` yaml $(tag) == 'schema-tianenappplatform-2020-11-26.1.2' && $(azureresourceschema)
output-folder: $(azureresourceschema-folder)/schemas

# all the input files in this apiVersion
input-file:
  - Microsoft.TianenAppPlatform/preview/2020-11-26.1.2/tianenappplatform.json
```
