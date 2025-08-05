# Terraform module for creating storage account in Azure



## Attributes to modify in module
| Name | Description |
|------|-------------|
|resource_group_name|The name of the resource group|
|location|The Azure region where the resource group will be created|
|storage_account_name|The name of the storage account to be created in the resource group|

## Outputs:

| Name | Description |
|------|-------------|
|resource_group_id|The ID of the resource group|
|storage_account_id|The ID of the storage account|