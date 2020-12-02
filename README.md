# Deploy Windows Virtual Desktop in Azure subscription
## Must be run in sequence
### First Step
#### Deploys below resources in Azure - 
- VNet
- Subnet
- AADS
- WVD workspace

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsssd-dev%2Ffantastic-octo-pancake%2Fmaster%2Faads.json)


### Second Step
#### Deploys below resources in Azure - 
- Host Pool

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsssd-dev%2Ffantastic-octo-pancake%2Fmaster%2Fhostpool.json)