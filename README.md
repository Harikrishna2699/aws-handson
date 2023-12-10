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

#3

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

#4

Classic load balancer creation


1.In the EC2 Dashboard, under the "Load Balancing" section in the left sidebar, select "Load Balancers."
2.Click on "Create Load Balancer":

3.In the Load Balancers section, click the "Create Load Balancer" button.
4.Choose Load Balancer Type:

5.Select "Classic Load Balancer."
6.Configure Basic Settings:

7.Provide a name for your load balancer.
8.Select the appropriate availability zones for your load balancer.
9.Choose the listener configuration (e.g., HTTP on port 80).
10.Configure Health Check:

11.Set up a health check to monitor the health of your instances. This includes specifying a ping target, port, and health check interval.
12.Add Instances:

13.Add instances (EC2 instances) to the load balancer. These are the instances that the load balancer will distribute traffic to.
14.Configure Security Groups:

15.Choose or create security groups for your load balancer. These security groups control the traffic to the load balancer.
16.Configure Security Settings (Optional):

17.Configure optional security settings such as idle connection timeout and cross-zone load balancing.
18.Configure Tags (Optional):

19.Add tags to your load balancer for better organization and identification.
20.Review Configuration:

21.Review the configuration settings for your load balancer.
22.Click the "Create" button to create your Classic Load Balancer
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/2df1cb28-a34b-4a86-8073-f52a9d4f2a8e)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/e59cea69-cdb9-43bc-931d-cc311f45d629)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/230c0e87-3cdb-4699-8f0c-e5b03e82fd11)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/f6dd1309-6ca0-451d-9f78-ad9089f00bb8)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/1b7bcd6e-b412-49c9-aa75-1b1a902905ea)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/ece0467d-8003-4302-9649-259ea4f24a0a)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/4cafab04-9096-4857-8c8c-751aed88a2a1)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/d97e644d-b33c-4c82-93a3-050ad2788264)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/b8926197-8a02-461c-900e-96b71d0f0b11)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/0f5f7620-15d5-41e8-b45f-ec26c8935954)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/c08b53e9-ab4a-460e-9440-2d6bb970c361)
![image](https://github.com/Harikrishna2699/aws-handson/assets/73926065/dd279288-d4bb-40f8-8e89-1403ea6426ef)













