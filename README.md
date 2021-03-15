# What this is about?

This project contains the relevant AWS `CloudFormation` templates and policy require to provision an EKS Cluster from scratch.

## Summary

1. [**`eks-vpc-private-subnets.yaml`**](https://github.com/syedimam0012/awsEKSCFNTemplates/blob/main/eks-vpc-private-subnets.yaml): Template to set up underlying networking components for control plane
2. [**`eks-cluster-role.yaml`**](https://github.com/syedimam0012/awsEKSCFNTemplates/blob/main/eks-cluster-role.yaml): Template to set up cluter role for control plane/master node
3. [**`eks-fargate-podexecution-role.yaml`**](https://github.com/syedimam0012/awsEKSCFNTemplates/blob/main/eks-fargate-podexecution-role.yaml): Template to set up `podesecution` role for fargate
4. [**`cni-role-trust-policy.json`**](https://github.com/syedimam0012/awsEKSCFNTemplates/blob/main/cni-role-trust-policy.json): Policy required by `IAM` role to be used for VPC CNI component
5. [**`amazon-eks-nodegroup-role.yaml`**](https://github.com/syedimam0012/awsEKSCFNTemplates/blob/main/amazon-eks-nodegroup-role.yaml): Template to create IAM role for the worker node

## :japanese_ogre: :japanese_ogre: :japanese_ogre:  in the Details

To realise the full potential of this project, navigate to [this medium post](https://medium.com/@syedimam0012/building-an-aws-eks-cluster-from-scratch-bfd2f5c6f3aa) 

