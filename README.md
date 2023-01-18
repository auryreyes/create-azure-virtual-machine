<p align="center">
<img src="https://i.imgur.com/qN6wRY9.png" height="50%" width="50%" alt="Banner"/>
</p>

<h1>Creating an Azure Account and Launching a Virtual Machine</h1>
Microsoft Azure is a cloud computing platform that offers a wide range of products and services. In this tutorial, we’ll register for a Microsoft Azure Subscription Account, use the portal and launch a Virtual Machine (VM).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

- Create Azure Account
- Azure Portal & Resource Group
- Create a Virtual Machine
- Connecting Virtual Machine to Microsoft Remote Desktop

<h3>Step 1: Create Azure Account</h3>
You can open an Azure account with $200 in free credit for 30 days.

<br>
<br>

Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

<p>
<img src="https://i.imgur.com/heVjJVa.png"/>
</p>
<p>
To make an account, simply follow the instructions on the website. It will be necessary to use a credit card, but you won't be charged until the $200 credit expires or the account has been open for a month. Congratulations! You are now a Tenant of Azure.
</p>
<h3>Step 2: Azure Portal & Resource Group</h3>
Let's discuss how to use the Azure portal now that the account has been set up. You can manage your subscriptions and locate all the items and resources on the platform. 

<br>
<br>

We will now launch a Windows 10 Virtual Machine but in order to do so, a Resource Group must be created. A Resource Group stores all the resources inside of Azure.


Create Resource Group
- Go to [portal](https://portal.azure.com/#home).
- Click “Create Resource Group”
- Name Resource Group as “VM-LAB-01”
- Review + Create -> Create
<br />

<p>
<img src="https://i.imgur.com/vIA8iMK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/e8kioSd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/xuIxKCB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/gCl5IgV.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 3: Create a Virtual Machine</h3>

Create Virtual Machine
- Go to [portal](https://portal.azure.com/#home)
- Click “Virtual Machines”
- Create -> Azure virtual machine
- Select Resource group: VM-LAB-01
- Region: (US) East US
- Virtual machine name: VM1
- Image: Windows 10 Pro
- Size: Standard_E2s_v3 - 2 vcpus, 16 GiB memory
- Username: labuser
- Create Password
- Check Licensing box
- Review + Create -> Create

Be sure to remember your username and password. Your virtual machine will show up in your resource group once your deployment is completed.

<p>
<img src="https://i.imgur.com/lS7Vh9E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Y7yqff1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/1XBIUVs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/LB4tfN5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/fD4a6i5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/qkWawip.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/KNBKQh7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 4: Connecting to Virtual Machine</h3>
The virtual machine's public IP address is initially required in order to establish a connection.

<br>
<br>

Locate Public IP Address
- Go to Virtual Machines
- Click “VM-LAB-01”
- Copy the Public IP Address

<p>
<img src="https://i.imgur.com/7tC8pZu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/o7SAMks.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/NKVNiCL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Connecting to Virtual Machine
- Go to start menu and type in “Remote Desktop Connection” and open the application
- Paste the Public IP Address and then select “Connect”
- Login with previous Username and Password created in Azure’s Virtual Machine portal
- Click “OK” and then select “Yes”

<p>
<img src="https://i.imgur.com/cVf1krh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/CY21pFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/wSJ1304.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/CBEnIbO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/J1o7clj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Congratulations! Your first Virtual Machine on Azure has been created.

<h3>!ATTENTION!</h3>


Because the majority of Azure services are pay-as-you-go, be sure to remove ALL resource groups and virtual machines if you want to keep your free $200 credits.

Delete Resource Groups and Virtual Machines
- Go to Resource groups
- Click VM-LAB-01 -> Delete resource group
- Type the resource group name then select “Delete”
- Repeat steps for all resources

<p>
<img src="https://i.imgur.com/6C6haJL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/tw5xULI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/GSAxtUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
