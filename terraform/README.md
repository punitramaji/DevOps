#Download terraform from https://www.terraform.io/downloads.html
wget https://releases.hashicorp.com/terraform/0.12.28/terraform_0.12.28_linux_amd64.zip
#unzip it 
sudo unzip terraform_*
#copy it to /usr/local/bin
cp terraform /usr/local/bin
terraform -version
terraform init
