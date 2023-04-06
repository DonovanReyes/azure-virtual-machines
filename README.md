<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Microsoft Azure is a cloud platform that will let you rent space in order to store or process your own data. This tutorial will showcase how to create a free Microsoft Azure account and create a virtual machine.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free $200 Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create Azure Account</h3>


Create an [Azure](https://azure.microsoft.com/en-us/free/) account
- Select Start Free
- Follow the prompt to create the account. 
     - You will need to put in your credit card information but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then.
- Finish prompt, click Go to Azure Portal and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


<p align="center">
<img src="https://imgur.com/T2okIVr.png" height="70%" width="70%" alt="Azure Free Account"/> 
</p>


<h3>Step 2: Create Resource Group</h3>

- Go to search bar at the top and search "resource group"
- Select create resource group
- You will then want to name the resource group and select the region 
- Select review + create
    - For this tutorial, we will be using RG-Lab01 for the name and (US) East US for the region

<p align="center">
<img src="https://imgur.com/ggbUJas.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/eQcY3TD.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>

<h3>Step 3: Create a storage Account</h3>

- Go to search bar and search "storage account"
- Select Create storage account
- You will need to select the resource group, the region, and create a name for the storage group
    - For this tutorial we will name the storage group storageacctutorial
    - Use same resource group and region as step 2
- Select review, then create.

<p align="center">
<img src="https://imgur.com/1cUiHxD.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/ASMBaug.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For this tutorial we will name the virtual machine VMtutorial
    - Use same resource group and region as step 2/3

<p align="center">
<img src="https://imgur.com/6swt4ST.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/Y67tTKW.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 



* You will then need to select image and size
    - For image we will use Windows 10 Pro
    - For size, select see all sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use Labuser
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://imgur.com/vc026Vp.png" height="70%" width="70%" alt="Azure Free Account"/>
</p>
 
     

<h3>Step 5: Connect to Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
   - Select the virtual machhine we created in step and the IP address will be on the right hand side 
   - Copy the IP address

<p align="center">
<img src="https://imgur.com/NcA9ljL.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Select continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://imgur.com/5Jicxs2.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/nqnZH2U.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>





Congratulations!👍 You have created your first virtual machine within Microsoft Azure!

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>NOTE</h3>
- Using virutal machines at times can be confusing as the desktop can mirror your personal computer's desktop. If you ever forget if you are on your vitual machine or your personal computer, follow this simple list.


 - First in the windows search bar type cmd which will highlight the Command Prompt app.
 - Open Command Prompt and type hostname followed by pressing the enter button.
 - Finally type whoami followed by the enter button.
 - Take note of how you can see that you are logged on in the Virtual Machine that you created on Azure.
  


<p align="center">
<img src="https://imgur.com/ZT1p9PW.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/QPn8R1k.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


-  Be sure to clean up and DELETE ALL your resources when you are done using your VMs, as they will eat up your credits behind the scenes!    
  
