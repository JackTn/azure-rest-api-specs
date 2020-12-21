## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

``` yaml $(azureresourceschema) && $(multiapi)
batch:
  - tag: schema-tianenapplicationinsights-2020-12-21
  
```

Please also specify `--azureresourceschema-folder=<path to the root directory of your azure-resource-manager-schemas clone>`.

### Tag: schema-tianenapplicationinsights-2020-12-21 and azureresourceschema

``` yaml $(tag) == 'schema-tianenapplicationinsights-2020-12-21' && $(azureresourceschema)
output-folder: $(azureresourceschema-folder)/schemas

# all the input files in this apiVersion
input-file:
  - Microsoft.TianenInsights/preview/2020-12-21/tianenapplicationinsights.json
```
