# Multi-API support for AutoRest v3 generators

> see https://aka.ms/autorest

``` yaml
input-file:
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/aiOperations_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentAnnotations_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentApiKeys_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentContinuousExport_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentFeaturesAndPricing_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentProactiveDetection_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/components_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/componentWorkItemConfigs_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/favorites_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/webTestLocations_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/webTests_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/analyticsItems_API.json
  - $(this-folder)/Microsoft.Insights/stable/2015-05-01/workbooks_API.json
  - $(this-folder)/Microsoft.Insights/preview/2017-10-01/eaSubscriptionMigration_API.json
  - $(this-folder)/Microsoft.Insights/preview/2017-10-01/componentFeaturesAndPricing_API.json
  - $(this-folder)/Microsoft.Insights/preview/2018-06-17-preview/workbooks_API.json
  - $(this-folder)/Microsoft.Insights/preview/2018-05-01/componentProactiveDetection_API.json
require: $(this-folder)/../../../profiles/readme.md
```