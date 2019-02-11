## Basic ARM Template Demo

1. In Visual Studio Code (http://code.visualstudio.com), navigate to [File] then [Open File...].
2. Open file ```https://github.com/caseywatson/BucDemo1/edit/master/BucDemo1/azuredeploy.json```.
3. Review the file and make any necessary changes.
4. Navigate to the Azure portal (https://portal.azure.com).
5. Open the Cloud Shell by clicking the >_ icon at the top of your screen.
6. Select the Bash interface.
7. Drag and drop the ```azuredeploy.json``` file into the Cloud Shell area. Wait for it to upload.
8. Create a new resource group through the Cloud Shell using the following command -
  - ```az group create --name [your resource group name] --location [group location (e.g., francecentral)]
9. Deploy the uploaded template to your newly created resource group using the following command -
  - ```az group deployment create --resource-group [name of resource group created in previous step] --template-file "azuredeploy.json"
