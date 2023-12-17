# 2048-EKS-deploy
2048-app-deploy-ingress

 ## 1) EKS (Amazon Elastic Kubernetes Service)
 Managed Control Plane: EKS takes care of managing the Kubernetes control plane components, such as the API server, controller manager, and etcd. AWS handles upgrades, patches, and ensures high availability of the control plane.

Automated Updates: EKS automatically updates the Kubernetes version, eliminating the need for manual intervention and ensuring that the cluster stays up-to-date with the latest features and security patches.

Scalability: EKS can automatically scale the Kubernetes control plane based on demand, ensuring the cluster remains responsive as the workload increases.

AWS Integration: EKS seamlessly integrates with various AWS services, such as AWS IAM for authentication and authorization, Amazon VPC for networking, and AWS Load Balancers for service exposure.

Security and Compliance: EKS is designed to meet various security standards and compliance requirements, providing a secure and compliant environment for running containerized workloads.

Monitoring and Logging: EKS integrates with AWS CloudWatch for monitoring cluster health and performance metrics, making it easier to track and troubleshoot issues.

Ecosystem and Community: Being a managed service, EKS benefits from continuous improvement, support, and contributions from the broader Kubernetes community.

## 2) Creating an AWS Account and Setting up IAM Users
Creating an AWS account is the first step to access and utilize AWS services, including Amazon Elastic Kubernetes Service (EKS). Here's a step-by-step guide to creating an AWS account and setting up IAM users:
1. Create an AWS Account
2. Access AWS Management Console
3. Set up Multi-Factor Authentication (MFA)
4. Configuring kubectl for EKS
## 3) Preparing Networking and Security Groups for EKS
Before launching an EKS cluster, we need to prepare the networking and security groups to ensure proper communication and security within the cluster.

1. Creating an Amazon VPC (Virtual Private Cloud)
2. Configuring Security Groups(Inbound Rules,Outbound Rules,Security Group IDs,Setting Up Internet Gateway (IGW) )
3. Setting Up Internet Gateway (IGW)
4. Configuring IAM Policies

By configuring IAM policies and associating them with IAM roles, you grant specific permissions to your EKS worker nodes, ensuring they can interact with AWS resources as needed while maintaining security and access control.

By completing these steps, your AWS environment is ready to host an Amazon EKS cluster. You can proceed with creating an EKS cluster using the AWS Management Console
