<!-- markdownlint-disable first-line-h1 -->
## Overview

[**default_location**](#overview) `string` (optional)

If specified, will set the Azure region in which region bound resources will be deployed.
Please see: [https://azure.microsoft.com/en-gb/global-infrastructure/geographies/][msdocs_azure_geographies]

## Default value

`"eastus"`

## Validation

None

> **IMPORTANT:** The default location must be a valid Azure region.

## Usage

Set the value to your [Azure region][msdocs_azure_geographies] of choice.

```hcl
  default_location = "uksouth"
```

> **TIP:** Changing this value will cause all location bound resources to be recreated

[//]: # "************************"
[//]: # "INSERT LINK LABELS BELOW"
[//]: # "************************"

[msdocs_azure_geographies]: https://azure.microsoft.com/global-infrastructure/geographies/ "Find the Azure geography that meets your needs"
