# Microsoft-Azure

<img width="884" alt="Screenshot 2025-01-23 at 7 59 52 PM" src="https://github.com/user-attachments/assets/14983237-8b1a-4703-8a5b-d5f0d3e188f9" />

<h1>Azure Virtual Machine Setup</h1>

This repository provides a guide to set up the necessary resources in Azure for our project. The setup includes creating a Resource Group, a Windows 10 Virtual Machine (VM), and a Linux (Ubuntu) Virtual Machine within the same Virtual Network (VNet) and Subnet. These resources will form the foundation for further project work.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Steps</h2>
<img width="387" alt="Screenshot 2025-01-23 at 8 10 04 PM" src="https://github.com/user-attachments/assets/886eb6b5-b6c1-4b4b-ae98-8415a69a6a3b" />


**1. Access Azure Portal**
    - Open the [Azure](https://portal.azure.com/) Portal.

**2. Create a Resource Group**

- Navigate to Resource Groups.
- Select Create.
- Provide a Resource Group Name and select a region.
- Click Review + Create and then Create.

<img width="50%" height="50%" alt="Screenshot 2025-12-23 085139" src="https://github.com/user-attachments/assets/bbab9dea-0752-4370-8c9d-44c6ecd58c1f" />


**3. Create a Windows 10 Virtual Machine**

- Navigate to Virtual Machines.
- Select Create > Virtual Machine.
- Provide the following details:
    - Resource Group: Select the Resource Group created earlier.
    - VM Name: Enter a name for your Windows 10 VM.
    - Image: Choose "Windows 10".
    - Authentication Type: Username/Password.
    - Allow Azure to create a new Virtual Network (VNet) and Subnet.
- Configure other settings as needed and click Review + Create and then Create.

<img width="50%" height="50%" alt="Screenshot 2026-01-13 081342" src="https://github.com/user-attachments/assets/efcc6fbc-7d97-4793-b588-61a3777e84f9" />



**4. Create a Linux (Ubuntu) Virtual Machine**

- Navigate to Virtual Machines.
- Select Create > Virtual Machine.
- Provide the following details:
    - Resource Group: Select the same Resource Group used for the Windows 10 VM.
    - VM Name: Enter a name for your Linux (Ubuntu) VM.
    - Image: Choose "Ubuntu Server".
    - Authentication Type: Username/Password.
    - Virtual Network: Select the previously created Virtual Network.
    - Subnet: Ensure it matches the Subnet of the Windows 10 VM.
- Configure other settings as needed and click Review + Create and then Create.

<img width="590" alt="Screenshot 2025-01-23 at 8 14 29 PM" src="https://github.com/user-attachments/assets/8d61e13a-a726-4966-94aa-7e3c594a4467" />
<img width="591" alt="Screenshot 2025-01-23 at 8 14 50 PM" src="https://github.com/user-attachments/assets/608a091a-568e-4fb5-aa28-df57a565dc9e" />
<img width="618" alt="Screenshot 2025-01-23 at 8 15 17 PM" src="https://github.com/user-attachments/assets/8cde4ee8-fef1-4186-a808-473033c8fa16" />


**5. Verify Setup**
- Ensure both VMs are in the same Virtual Network and Subnet.




<h2>Purpose</h2>

The purpose of this repository is to create the essential Azure resources—Virtual Machines, Resource Group, and Virtual Network—required to begin our project. The setup ensures both VMs are in the same Virtual Network and Subnet for seamless communication.
