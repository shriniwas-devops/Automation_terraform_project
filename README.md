DevOps project using Git, GitHub, Jenkins and SonarQube, Nexus ,Terraform , AWS.

An end to end Automated Infrastructure using terraform.

In this project, we will be see how create Automated infrastructure using terraform.

*Follow this project *

Project Architecture

<img width="788" alt="terraform" src="https://user-images.githubusercontent.com/122585172/230704921-bdc325c0-1266-4579-9e7e-5ef8fb593d9c.png">


![fghfghgfj](https://user-images.githubusercontent.com/122585172/230704923-b94d7949-97de-48ca-89c8-5ccddd7185ce.png)


Project Info:

=> coming to digram here this is the vpc and inside this vpc we are having 6 subnet so you can see green one is indicating like the number of public subnet we have.

=> and the blue on eis indicating these are private subnet that we have and inside some you can see instances are runing these are instances jenkins ,sonarqube and one more nexus 


PreRequisites:

1 Git

2 Github

3 Jenkins

4 SonarQube

5 AWS VPC,S3,EKS,EC2



In this Project below are the things discussed.

1. Build a Reusable module
2. Multiple VPC Creation
3. Multiple Subnets Creation
4. Public | Private Subnets Creation
5. Internet Gateway Creation
6. Route Table creation
7. Route table association
8. Eks cluster + IAM roles+ Policies
9. NodeGroup Creation + IAM ROLEs +Policies


So here we are going to create one VPC and (2 public subnet + 2 private subnet)

I am going to create config folder and modules we have 2 folder which i will keep all of my modules here and after that we will have many many files.

we will have main.tf and we will have variables.tf and after that we need version.tf and provider.tf

coming to modules part inside modules part i will create multipal folder here going to moudule i have a folder like aws_vpc , aws_subnet , aws_s3_aws_igw , aws_elstic_ip , aws_eks , aws_eks_nodegroup , aws_route_table , aws_route_table_association etc.



Push all the terrform infrastructurecode file into github


![fgd](https://user-images.githubusercontent.com/122585172/230705932-195149d6-876b-4f3d-ba2f-a18074aeeead.png)



output:

Terraform plan  command after output:

![DSFD](https://user-images.githubusercontent.com/122585172/230717405-4e1a130c-67ea-4be4-bc64-8f56ca2eaf37.png)

Terraform apply command after output:


![FDGGFD](https://user-images.githubusercontent.com/122585172/230717439-6087a616-0782-4665-a4a3-54fc589b6032.png)




