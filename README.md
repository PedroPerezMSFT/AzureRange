# AzureRange
Generates Complementary Subnets of Azure Datacenter IP Ranges. Live site is at http://azurerange.azurewebsites.net

#Future Plans
>- Ability to select the Azure Region to be more specific of which region you want to allow direct access from your VNet without packets being forced back towards the peering location.
>- Ability to add custom IP prefixes for the customer to exclude specific ranges from the forced tunelling approach. For example, you might have an PaaS service or other web service that isn't part of Azure but for which you would still want Azure VNet resources to access that service without hairpinning back on premise. 
