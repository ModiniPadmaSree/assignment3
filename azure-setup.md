Create an Azure account
1. Go to the Azure Website: Navigate to the official Microsoft Azure homepage
2. Select an Account Option: Choose the "Start Free" button to begin the sign-up process for a free account that includes a credit (e.g., USD$200 for the first 30 days) and free access to services. Alternatively, you can select the "Pay as you go" option
3. Sign In or Create a Microsoft Account: Use an existing Microsoft email address and password to sign in, or create a new account.
4. Provide Personal Information: Fill in your details, including your name, country/region, and phone number.
5. Verify Your Identity: Microsoft will send a verification code via email or text message to the contact information you provided
6. Enter Payment Information: Provide a valid credit or debit card for identity verification purposes
7. Agree to Terms and Conditions: Review and accept the Azure subscription agreement and privacy statement.
8. Complete Sign Up: Click the "Sign up" or "Create account" button to finalize the process.

Setup a VM instance
1. Sign in to the Azure portal: Access the Azure portal using your credentials.
2. Navigate to Virtual Machines: Search for "Virtual machines" in the search bar or find it in the Azure services menu.
3. Create a new Virtual Machine: Select "+ Create" and then "Virtual machine."
4. Subscription & Resource Group: Choose your Azure subscription and create a new resource group or select an existing one.
5. Instance Details: Provide a unique name for VM, select the desired region, and choose an appropriate operating system image (Ubuntu Server).
6. Size: Select the VM size(b1s) based on your performance and cost requirements.
7. Configure the administrator account, either by creating a new username and password or by using an SSH public key.
8. Inbound Port Rules: Specify which public inbound ports to allow (e.g., SSH for Linux).
9. Review and Create: Review your chosen settings on the "Review + create" tab. Once validation passes, select "Create" to deploy your VM.
10.Connect to the VM: After deployment, navigate to VM's overview page and use the "Connect" option to establish a connection(SSH for Linux).

Deploying python:
1. Install python by - apt install python
2. Write python scripy - nano file.py
3. Run code - python3 file.py
