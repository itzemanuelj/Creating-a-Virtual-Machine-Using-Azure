8<p align="center">
<img src="https://i.imgur.com/3iwtTkN.jpeg height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>


# Creating a Virtual Machine Using Azure


## Prerequisites and Installation

This tutorial outlines the prerequisites and installation steps for Creating a Virtual Machine Using Azure

## Environments and Technologies Used
 **Azure Portal**
- **The Azure Portal is the main web interface for creating, configuring, and managing Azure VMs and other resources.** 
- **Usage: It offers a visual interface to select VM types, configure networking, assign storage, set up security, and manage monitoring options.**


## Operating Systems Used
-  **Azure VMs can run Windows Server for enterprise and web hosting, various Linux distributions like Ubuntu, CentOS, and RHEL for open-source projects and development, while macOS can be used for connecting to and managing VMs using tools like Azure CLI and PowerShell.** 

## List of Prerequisites

- **Azure Account** 
- **Computer with Internet Connection**
- **Credit Card (Required for free Azure credits)**

## Installation Steps

### Step 1: Create an Azure Account 


Create an Azure account [here](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=azurefreeaccount).
    -  Follow the prompt to create the account 
    -  You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then.
    -  Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!

### Additionally If You Already Have An Account Go To [portal.azure.com](https://www.portal.azure.com) To Start
&nbsp;

![Azure Sign Up](https://i.imgur.com/jhPlHcM.png)

### Azure Portal Login
![Azure Portal Login](https://i.imgur.com/5xXXBKu.png)

### Step 2: Create a Resource Group  

1. Go to the Azure portal search bar at the middle top of the screen and search **resource group**.
2. Select Resource Group.
3. In the Resource Group tab click **Create**.
3. We then need to name the resource group and select the region.
4. In this tutorial we will name the resource group **resourcegroup1** and select **(US) East US** for the region.
5. On the bottom left of the screen click **Review + Create**
6. Once verification is complete we have successfully  created a Resource Group . We can then click **Create** at the bottom right of the screen. 
&nbsp;

![Azure RG](https://i.imgur.com/RoeNEDQ.png)
![Azure RG](https://i.imgur.com/1U1NmMl.png)
![Azure RG](https://i.imgur.com/6WO3Ffb.png)
![Azure RG](https://i.imgur.com/vUn410f.png)
![Azure RG](https://i.imgur.com/2EZSOat.png)

### Step 3: Create a Storage Account
1. Go to the Azure portal search bar at the middle top of the screen and search **Storage Account**.
4. Click **Create** on the left top side of the screen or on the bottom middle.
3. We need to select the same **Resource Group and Region** and click **Create Storage Account**.
4. In this tutorial we will name the Storage Account **storageaccount1** and select **(US)East US** for the region.
5. At the middle of the screen we will select **Review + Create** and click **Create**.
6. Our Storage Account is now successuccessfully created . 
&nbsp;

![Azure RG](https://i.imgur.com/Eeygknm.png)
![Azure RG](https://i.imgur.com/y95jXBl.png)
![Azure RG](https://i.imgur.com/D0xT4ET.png)

### Step 4: Create a Virtual Machine
1. Go to the Azure portal search bar at the middle top of the screen and search **Virtual Machine**.
2. Click Create Azure Virtual Machine at the middle bottom of the screen of the page.
3. We will need to select the same **Resource Group**, **Region**, and create a name for the virtual machine
4. In this tutorial, we will name the virtual Machine **"Windows10ProVM"**
5. We now need to select an Image for our virtual machine.
6. In this tutorial, we will be using a **Windows 10Pro VM image**.
6. Next scroll down to size , we need to select which VM size. 
6. Finally, we will create a username and password so we can login to our VM.
>9. Make sure to confirm and agree to licensing agreements .
10. Once validation is passed we have now successfully  created our VM.
&nbsp;

![VM](https://i.imgur.com/Znvhn2a.png)
![VM](https://i.imgur.com/g8Nd8SJ.png)
![VM](https://i.imgur.com/VlfgZCZ.png)
![VM](https://i.imgur.com/Ffi9sTU.png)
![VM](https://i.imgur.com/DnXpLVI.png)
![VM](https://i.imgur.com/I9lXRRf.png)
![VM](https://i.imgur.com/B9KSSRc.png)
![VM](https://i.imgur.com/5KfUJPb.png)


### Step 5: Connect to the Virtual Machine
1. First we need to find the public IP Address of our virtual machine.
2. Select the virtual machine we created and copy the public IP Address on the right side of the Virtual Machine of the screen.
3. Open up Remote Desktop Connection or type **MSTSC** in our search bar . 
4. In Remote Desktop Connection we can then now paste in  our IP Address.
5. Enter username and connect. &nbsp;

![VM](https://i.imgur.com/3dlD3Ea.png)
![VM](https://i.imgur.com/FUMEMaf.png)
![VM](https://i.imgur.com/kSmOE3Z.png)

### Step 6: Connect to the Virtual Machine
1. Enter username and password that we created prior to creating our VM.
2. 🎉Congratulations! You have created your first virtual machine within Azure!🎉

![VM](https://i.imgur.com/mVm8WEE.png)
![VM](https://i.imgur.com/wEaETOZ.png)

---

> For more details, visit the [Azure](add).

## FAQ
**Q.What are Azure Virtual Machines (VMs)?** <br>
A: Azure VMs are scalable, on-demand virtual machines that allow users to deploy, manage, and maintain virtualized instances. They support various operating systems and can run applications as if on a physical server. 

**Q. What is Microsoft Azure?** <br>
A: Azure is Microsoft's cloud computing platform that provides a range of services such as virtual machines, databases, and storage. It supports building, deploying, and managing applications through Microsoft-managed data centers. 
-- -
## Conclusion
You’ve successfully created a Vitrual  Machine in Azure.
