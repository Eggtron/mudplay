# mudplay

Install the SDK

sudo apt-get update  
sudo apt-get install -y apt-transport-https  
sudo apt-get update  
sudo apt-get install -y dotnet-sdk-6.0  

Install Mudblazor

dotnet new --install MudBlazor.Templates  
dotnet new mudblazor --host wasm --name MyApplication  