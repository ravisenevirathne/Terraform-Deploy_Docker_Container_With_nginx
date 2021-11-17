# Terraform-Deploy_Docker_Container_With_nginx .

sources are in Master Branch

Terraform install on PC using choco

- Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
- choco install terraform
- terraform version

- Terraform init .
- Terraform apply
- docker ps  
- Terraform Destroy

..
......


Further detail https://www.youtube.com/watch?v=ItIFWFutUCA
