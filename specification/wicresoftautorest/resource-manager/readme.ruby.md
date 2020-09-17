## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_wicresoftautorest
package-version: 2020-09-17
azure-arm: true
```

### Tag: package-2020-09-17 and ruby

These settings apply only when `--tag=package-2020-09-17 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2020-09-17' && $(ruby)
namespace: Microsoft.WicresoftAutoRest
output-folder: $(ruby-sdks-folder)/wicresoftautorest
```
