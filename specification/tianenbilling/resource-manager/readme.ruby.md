## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_tianenbilling
package-version: 2020-09-22
azure-arm: true
```

### Tag: package-2020-09-22 and ruby

These settings apply only when `--tag=package-2020-09-22 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2020-09-22' && $(ruby)
namespace: Microsoft.TianenBilling
output-folder: $(ruby-sdks-folder)/tianenbilling
```
