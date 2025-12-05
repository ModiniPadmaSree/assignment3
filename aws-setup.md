Creating an AWS Account

1. Visit the official AWS website.
2. Click Create a new AWS account.
3. Enter your email address, password.
4. Choose any plan free or pro.
5. Add personal detail  like contact number and address.
6. Provide valid billing information such as payment method cards or upi id and details of the method chosen and address  
7. Complete phone verification using an OTP.
8. Log in to the AWS Management Console using root user mail id.

Setup basic EC2 instance
1. Log in to the AWS Management Console: Access the console and navigate to the EC2 dashboard.
2. Choose a Region: Select the AWS geographical region where the EC2 instance will be launched.
3. Launch Instance: Click on "Launch instances" to begin the instance creation process.
4. Name and Tags: Provide a descriptive name for the instance and add any relevant tags for organization. 
5. Choose an Amazon Machine Image (AMI): Select an AMI, for the instance's operating system and software includes 
   Amazon Linux, Ubuntu, Windows, etc. Choose Ubuntu
6. Choose an Instance Type: Select an instance type based on the required CPU and memory. 
   For testing or basic usage, the t2.micro instance type is suitable.
7. Configure Key Pair: Create a new key pair or choose an existing one.
   If creating a new key pair, provide a name and download the private key file (e.g., .pem for Linux/macOS or .ppk for Windows).
8. Network Settings:Configure network settings, including the VPC, subnet, and security groups.
   The security group allows inbound traffic on the necessary ports (e.g., SSH on port 22).
9. Configure Storage: Specify the storage volume size and type for the instance.
10. Launch Instance: Review the configurations and click "Launch instance."
11. Connect to the Instance: Once the instance is in a running state, connect to it using SSH (for Linux) using the downloaded key pair and the instance's public IP address.
