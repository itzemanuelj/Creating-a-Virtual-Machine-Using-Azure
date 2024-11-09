Creating a Virtual Machine Using Azure (ELI5)

![Azure Logo](images/azure-logo.png)

# Creating a Virtual Machine Using Azure (ELI5)

This guide will help you create a **Virtual Machine (VM)** on **Microsoft Azure** so you can run an operating system (like Windows or Linux) on a cloud server.

## What You Need
- **Microsoft Azure account** (sign up at [Azure](https://azure.microsoft.com/) if you don’t have one).
- Basic knowledge of your preferred **Operating System** (e.g., Windows or Linux).

---

## Step-by-Step Guide

### Step 1: Log in to Azure
1. Go to the [Azure Portal](https://portal.azure.com/) and sign in with your Azure account.
2. Once logged in, you’ll see the Azure dashboard.

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)


### Step 2: Create a Virtual Machine
1. From the Azure dashboard, select **Create a resource**.
2. In the search bar, type **Virtual Machine** and click on the **Virtual Machine** option that appears.
3. Click **Create** to start setting up your new VM.

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)

### Step 3: Configure Basic Settings
1. Choose your **Subscription** and **Resource Group**. If you don’t have a resource group, create a new one.
2. Under **Instance Details**, set the following:
   - **Region**: Choose a data center close to you.
   - **Image**: Select the operating system you want (e.g., Windows 10, Ubuntu Linux).
   - **Size**: Choose the VM size based on your needs (basic configurations work for most beginners).
3. Set a **Username** and **Password** for your VM (you’ll use these to log into the VM later).

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)

### Step 4: Configure Additional Settings
1. In the **Disks** tab, choose the storage type for your VM (Standard SSD works for most cases).
2. In the **Networking** tab, ensure **Public IP** is enabled so you can connect to your VM.
3. Leave other settings at their default unless you need specific customizations.

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)


### Step 5: Review and Create
1. Click **Review + create**.
2. Review the settings you’ve chosen. If everything looks good, click **Create** to start the deployment.

### Step 6: Wait for Deployment
Azure will take a few minutes to set up your VM. You’ll receive a notification once it’s ready.

![Azure Logo](images/azure-logo.png)

![Azure Logo](images/azure-logo.png)

---

## Connecting to Your Virtual Machine

### Step 7: Connect to Your VM
1. Go to the **Virtual Machines** section in Azure and select your new VM.
2. Click **Connect** at the top and choose the connection method:
   - **RDP** for Windows VMs
   - **SSH** for Linux VMs
3. Follow the instructions provided to log into your VM using your **Username** and **Password**.

---

> **Note:** Ensure you understand any associated costs with running a VM on Azure, as charges may apply based on the size and usage of your VM.

## FAQ

**Q: Do I need to keep my VM running?**  
A: No, you can **stop** the VM when not in use to avoid extra charges. You’ll find this option in the VM’s settings.

**Q: What if I want to change the VM settings later?**  
A: Azure allows you to resize, reconfigure, and modify your VM settings anytime from the **Azure Portal**.

---

## Conclusion
You’ve successfully created a VM on Microsoft Azure! You can now use it to run programs, host applications, or experiment with different operating systems. For more details, visit the [Azure Documentation](https://docs.microsoft.com/azure/virtual-machines/).

--- 