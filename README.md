# Terraform
resource-group = {

"Dev-RG" = "southindia"
"QA-RG" = "westindia"
"Prod-RG" = "centralindia" }
vnet = {

"Vnet_Address" = ["10.0.0.0/16",]
"Vnet_Name" = "Dev-Vnet" }
subnet = {

"Web-Subnet" = ["10.0.1.0/24",]
"App-Subnet" = ["10.0.2.0/24",]
"DB-Subnet" = ["10.0.3.0/24",]
}
