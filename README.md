# Azure-ARM-Templates
In order to create the Resources from the Template in this repository we need to run the following commands first.

Create the Resource group

"
 az group create `
--name vscode `                     
--location 'eastus'
"

Run the ARM template file with the below command.

"
 az deployment group create `
 --resource-group vscode ` 
 --template-file create-vm.json
"
