# HashiCorp Terraform Practice

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

**2. Build Infrastructure**

In the second tutorial, I provisioned an EC2 instance on AWS.

**Prerequisites**
First I had to configure the aws cli which I had installed by running _aws configure_ and then following the prompts to input my AWS Access Key ID and Secret Access Key.

---

After creating the main.tf file I ran the following commands to provision the EC2 instance

```
terraform init
terraform fmt
terraform validate
terraform apply
```

![](/images/ec2.png)

![](/images/show.png)

To destroy the provisioned infrastructure I ran

```
terraform destroy
```

![](/images/destroy.png)
