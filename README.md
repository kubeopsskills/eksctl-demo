# Create an EKS Cluster using Terraform and EKSCTL

## Prerequisites:

- [Terraform](https://www.terraform.io/downloads)
- [EKSCTL](https://docs.aws.amazon.com/eks/latest/userguide/eksctl.html)
- [AWS Profile Configuration](https://github.com/kubeopsskills/awsp)

### 1. Run the following commands to create a VPC network

#### 1.1 Prepare your VPC network configuration in "network.tf" file

#### 1.2 Run "terraform plan" command to review your VPC network configuration

```sh
$ terraform plan
```

#### 1.3 Run "terraform apply" command to create your VPC network

```sh
$ terraform apply
```

### 2. Run the following commands to create an EKS Cluster

#### 2.1 Prepare your EKS Cluster configuration in "eksctl-cluster.yaml" file

#### 2.2 Run "eksctl create cluster" command to create the EKS Cluster

```sh
$ eksctl create cluster -f eksctl-cluster.yaml
```

### 3. Let's fun with EKS !
