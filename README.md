### Governance Interview 

As an organization, we would like to restrict new resources from being created in non-approved regions. Create an Azure policy definition that can ensure new resources will not be placed in any region except:
* East US
* West US

We would like the finished definition and assignment to be created in terraform using:      
[azurerm_policy_definition](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/policy_definition.html)     
[azurerm_subscription_policy_assignment](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subscription_policy_assignment)


#### Steps:
1. Open https://vscode.dev/github/jakebair-delinea/governance-interview
2. Create Codespace -or- clone locally and open devcontainer
3. Login to Azure CLI `az login --use-device-code`
4. Initialize Terraform
5. Create Policy Definition
6. Assign Policy