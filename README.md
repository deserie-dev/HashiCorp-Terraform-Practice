<div align="center">HashiCorp Terraform Practice</div>

Terraform is one of the Infrastructure as Code (IAC) tools I'm learning in the SheCodeAfrica Cloud School.

I'm using tutorials from [Terraform's official website](https://learn.hashicorp.com/tutorials/terraform/infrastructure-as-code?in=terraform/aws-get-started)

**Pre-Requisite**

[Install Terraform](https://www.terraform.io/downloads.html)

**1. Quick start tutorial**

I provisioned an NGINX server using Docker on Windows. I already had Docker for Desktop installed from previous tasks. After creating the main.tf file I ran the following commands to provision the NGINX server

```
terraform init
terraform apply
```

![](/images/apply.png)

![](/images/dockerdesktop.png)

![](/images/nginx.png)

I ran _docker ps_ to see the container

![](/images/dockerps.png)
