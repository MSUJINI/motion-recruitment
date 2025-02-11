Step 1: Create an Azure Account
Visit the Azure Website:

Go to the Microsoft Azure website.
Start Free with Azure:

Click on the "Start free" button.
Sign Up for an Account:

If you already have a Microsoft account (like Xbox Live, Outlook, etc.), you can use that to sign in. Otherwise, create a new Microsoft account.
Provide your personal information including name, phone number, and email address.
Identity Verification:

Verify your identity using a phone call or SMS.
Provide a valid credit card or payment method for verification (you won’t be charged unless you exceed the free tier limits).
Complete the Signup:

Review the provided information and complete the signup process.
You will receive a confirmation email once your account is set up.



Step 2: Set Up a Basic Azure VM
Log in to the Azure Management Portal:

Use your credentials to log in to the Azure Portal.
Navigate to the Virtual Machine Service:

In the Azure Portal, use the search bar at the top to search for "Virtual Machines".
Click on "Virtual Machines" in the search results.
Create a Virtual Machine:

Click on the "Create" button and select "Virtual Machine" from the drop-down options.
Configure the Basics:

Subscription: Choose your active subscription.
Resource Group: Create a new resource group or use an existing one.
Virtual Machine Name: Give your VM a name.
Region: Choose a region that is closest to you.
Availability Options: Choose the default or desired availability.
Image: Select the operating system (e.g., Ubuntu Server, Windows Server).
Size: Choose the VM size (e.g., B1s or other basic tiers as per free limits or requirements).
Configure the Administrative Account:

Authentication Type: Choose between SSH public key or password.
Username: Create a username for your VM.
Password/SSH Public Key: Depending on your selection, set up the authentication method.
Configure Networking:

Select or create a virtual network.
Ensure that a public inbound port rule for SSH (port 22) or RDP (port 3389) is set up, depending on your OS.
Set Management and Monitoring Options:

Configure monitoring, diagnostics, and auto-shutdown options as needed.
Review and Create the VM:

Review all configurations and click "Create".
Wait for Azure to deploy the VM. You will see a notification once it is ready.



Step 3: Deploy a Sample Python Script
Connect to Your Azure VM:

For Linux VMs, use SSH:
Open your terminal or command prompt.
Use the SSH command provided by Azure to connect to your VM.
For Windows VMs, use Remote Desktop (RDP):
Use the Remote Desktop Connection application and the provided credentials to connect.
Install Python (if not already installed):

Update the package index.
Install Python using the appropriate package manager for your operating system.
Create a Python Script:

Using a command-line text editor (like nano, vim, or your preferred editor), create a new file (e.g., add_numbers.py).
Write the Python code to add two numbers. (The script should prompt for input or include hardcoded values for simplicity.)
Run the Python Script:

Execute the script using the Python interpreter to ensure it works as expected.
Considerations for Optimisation and Competitive Programming
Automation:

Use Azure CLI or Azure Resource Manager (ARM) templates to automate the VM setup and deployment process.
Consider using scripting languages such as PowerShell or Bash to automate repetitive tasks.
Security Best Practices:

Ensure inbound security rules are configured minimally and securely.
Regularly update and patch the VM to keep it secure.
Cost Management:

Monitor resource usage and set up alerts to avoid unexpected charges.
Leverage Azure’s free tier and reserved instances for cost savings where applicable.

hence by following above steps we can complete azure setup...