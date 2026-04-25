## Azure Storage Account File Upload Lab

## Project Summary
This project demonstrates how to use Microsoft Azure to create a resource group, deploy a storage account, upload and edit a file, and verify the changes were made.

- Project Type: Cloud lab / walkthrough  
- Languages Used: None  
- Environment Used: Azure Portal, local desktop  
- Technologies Used: Azure Resource Groups, Azure Storage Accounts  

## Demonstration

### Step 1: Create Azure Account
Head over to "portal.azure.com" to either create an account or log into an existing one. You can make a free account or paid one, but a paid account will not be necessary for this project.

### Step 2: Create Resource Group
On the left side of your screen, find the Resource Groups tab. Click it, and then find "create" and click that as well. Give it a name, something simple and easy to remember. Then click "review and create". A pop up window should appear saying "Resource Group Created."

### Step 3: Create Storage Account
Return to the left hand side of the dashboard screen, find Storage Accounts. In the drop down menu next to Resource Group, select the one you just created. Give it a name, something with only lowercase letters and numbers and it must not already be taken. Select your region, for storage type select Azure Blob Storage, Standard Performance, for Redudancy select Locally Redundant Storage. Select "Review and Create", then "Create". Wait for deployment, once deployed, you should get a pop up telling you it was successful.

### Step 4: Create Text File
On whatever computer you're using, create a text file, set the format to "plain text". Write something simple. Reenter Azure, Go back to Storage Accounts and find the one we just made.

### Step 5: Upload File
 Select Upload. Upload your file, create a container and give it a simple name with all lowercase letters and numbers. Upload. 

### Step 6: Edit File
Go back to the Storage Containers screen, on your left, scroll down to find containers. Click on the one we just created. Open the text file. At the top, select "Edit". Edit the text file, select save.

### Step 7: Download File
Select Download, add it somewhere easy to find like yiour desktop. Verify that the changes were made. 

## Media

(Screenshots are in the files section.)
