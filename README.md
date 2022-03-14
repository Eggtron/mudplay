# mudplay

Install the SDK

wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb  
sudo dpkg -i packages-microsoft-prod.deb  
rm packages-microsoft-prod.deb  

sudo apt-get update  
sudo apt-get install -y apt-transport-https  
sudo apt-get update  
sudo apt-get install -y dotnet-sdk-6.0  

Install Mudblazor

dotnet new --install MudBlazor.Templates  
dotnet new mudblazor --host wasm --name MyApplication  