 #1 
 
EC2 INSTANCE CREATION

STEP:1 CLICK ON COMPUTE AND MOVE TO EC2 INSTANCE

STEP:2 LAUNCH INSTANCE

STEP:3 CHOOSE AMI 

STEP:4 CHOOSE INSTANCE TYPE

STEP:5 SETUP KEY PAIR 

STEP:6 SETUP NETWORK CONFIGURATION

STEP:7 ADD STORAGE

STEP8: LAUNCH INSTANCE 

![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/02204229-e40b-4657-ae7e-c3cd6f1b2535)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/a1fda8f6-b27e-43c1-8034-93d7a9ce7874)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/57b05c66-2714-4dfc-a404-f79e73556281)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/4e62847a-4fe5-429a-b47d-bfb8f56d1f2c)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/4dd5ea68-8d80-4901-84e0-0063b5aa3e84)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/8615b992-84c3-40d6-9a8e-49856f654544)



#2

Application Hosting in windows instance

STEP:1 LAUNCH EC2 INSTANCE

STEP:2 CLICK CONNECT BUTTON AND CLICK RDP CLIENT
 CHECK USERNAME AND CLICK GET PASSWORDUPLOAD PRIVATE KEY FILE WHICH WE HAVE CREATED EARLY AND DECRYPT THE PASSWORD

STEP 3: CLICK WINDOWS BUTTON AND OPEN REMOTE DESKTOP CONNECTION
ENTER THE PUBLIC IP ADDRESS OF CREATED INSTANCE
AFTER CONNECTING REMOTE DESKTOP CONNECTION ,NEW WINDOWS VIRTUAL SERVER WILL OPEN

STEP:4
AFTER CONNECTING THE VIRTUAL SERVER,WE HAVE TO INSTALL MIDDLEWARE FOR APPLICATION HOSTING
i)WE HAVE TO INSTALL IIS(webserver)
OPEN SERVER MANAGER IN VIRTUAL WINDOWS
CLICK ADD ROLES AND FEATURES

STEP:5
AFTER SUCCESSFULLY INSTALLED IIS WEBSERVER , WE HAVE TO DEPLOY SOURCE FILE IN INSTANCE,FOR THAT
COPY THE SOURCE FILE AND PASTE IN VIRTUAL SERVER 
PATH[C DRIVE--->INET PUB-->WWWROOT--->PASTE THE SOURCE CODE FOR DEPLOY

STEP:6
AFTER DEPLOY CODE IN PARTICULAR PATH,WE HAVE TO COPY PUBLIC IP ADDRESS IN INSTANCE.

STEP:7 AFTER PASTE THAT IP ADDRESS IN BROWSER ,WE CAN SEE OUR APPLICATION IN SERVER

![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/49711fc1-05a3-442e-850e-136f8d191a41)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/7452a6dc-bcdc-4c23-8bed-baf29e49f930)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/beb2895d-e795-46d2-8e97-5b414042ec9b)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/6607e73d-92a8-4fa0-a2ed-d990f8ad1b41)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/10a6e05d-4b93-49d9-a237-7bf7e368075a)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/40ff2348-4170-48d5-aa25-b13203728c65)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/be571749-050d-4500-865a-62728a45e608)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/b67aac88-b041-4066-aeca-0fc1fcaf58b9)

VPC CREATION


1.Provide a name for your VPC.
2.Specify the CIDR (Classless Inter-Domain Routing) block for your VPC. This defines the IP address range for your VPC. For example, 10.0.0.0/16.
3.Configure Subnet Settings:

4.Add one or more subnets to your VPC. Each subnet should be associated with a specific availability zone and should have its own CIDR block within the VPC CIDR range.
5.Configure Route Tables:

6.Create one or more route tables for your VPC. A route table contains a set of rules, called routes, that are used to determine where network traffic is directed.
7.Configure Internet Gateway (Optional):

8.If your VPC needs to connect to the internet, create an Internet Gateway and attach it to your VPC. This allows instances in your VPC to communicate with the internet.
9.Configure Security Groups:

10.Create and configure security groups for your VPC. Security groups act as a virtual firewall for your instances to control inbound and outbound traffic.
11.Configure Network ACLs (Optional):

12.Network ACLs are an optional layer of security for your VPC. You can create network ACLs with rules to control traffic at the subnet level.
13.Review and Create:

14.Review the configuration settings for your VPC.
15.Click the "Create VPC" button to create your VPC with the specified settings.
16.Wait for VPC Creation:

![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/1eb06d36-6eb6-4047-b66d-186993828b41)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/1a42bfd8-8182-4dad-918b-390238e0ba15)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/4480788d-a4c3-4483-8bc0-561905ba5404)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/1d444944-a762-48bd-8ca2-014dce09b456)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/5ea73669-cd42-467f-bf56-c59d7b330085)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/f59f1396-c032-4f47-baa6-851b980dfb01)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/2957f8f0-1853-4129-924e-6c4f0e4bf56c)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/1320a94a-446b-4ac5-982c-b32591c0443c)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/fbfb2c19-9e6b-4a38-bb93-2ef168dc37a9)  
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/8292c580-418e-4680-8a7c-216620191437)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/7da11d9d-10fd-4e50-acd4-19e06fbf7ae6)















