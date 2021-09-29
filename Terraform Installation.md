**Install Terraform**

   **#Below Step's are for Amazon Linux**

» Install yum-config-manager to manage your repositories.
  
    sudo yum install -y yum-utils

» Use yum-config-manager to add the official HashiCorp Linux repository.

    sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

» Install.

    sudo yum -y install terraform
    
» Verify the installation
      
      terraform -help    
