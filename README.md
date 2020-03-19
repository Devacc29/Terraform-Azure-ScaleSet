# Terraform Azure ScaleSet with R80.30 gateway
Check Point Lab deployment with ScaleSets and Windows/Linux Jump Servers

The demo requires that the autoprovisioning is already setup with an existing R80.30 or later management server

Adjust the tags on the ScaleSet to match your profile in the autoprovisioning setup as part of Check Point Azure Scale Set Solution

- Based on R80.30 gateways with Terraform v0.12 syntax.
- Simple setup with multiple DMZ's and route tables. 
- Linux Jump Server with public IP to gain access to the enviroment
- Windows RDP via the ScaleSet to a jump host behind the gateway for testing
