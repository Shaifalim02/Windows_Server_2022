# Windows-Server-2022
Successfully Deployed Windows Server 2022 with Active Directory! 
Excited to share that I have successfully set up Windows Server 2022 along with Active Directory Domain Services (AD DS)! 

### 🧠 What You’ll Learn
- How to deploy and manage a Windows Server 2022 virtual machine in Azure
- Installation and configuration of Active Directory Domain Services (AD DS)
- Creating a new domain and promoting a server to a Domain Controller

### 🔹Key Steps in the Setup Process:
- Created an Azure Virtual machine
- Installed Windows Server 2022 through Microsoft Azure
- Configured essential server roles & features
- Created a new Active Directory Forest (Server.local)
- Promoted the server to a Domain Controller

### ScreenShots WalkThrough
| Steps | Description | ScreenShot |
|-------|-------------|------------|
|  1️⃣  | Azure Portal interface where users manage their virtual machines (VMs). Accessed it via Remote Desktop and began configuration using Server Manager. | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/8990e543770d816af5d0fbb52cf10a2ac3182821/image.png) |
| 2️⃣   | Stepped into the Add Roles and Features Wizard on Windows Server 2022 to begin configuring essential services. From selecting the installation type to choosing the destination server, this process lays the groundwork for installing roles like Active Directory Domain Services. | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/7016a5884228af6273629b74566805a92eb187f4/image%201.png) |
| 3️⃣   | Installing Active Directory Domain Services (AD DS) on Windows Server 2022 via the Add Roles and Features Wizard. It includes selecting the server role and viewing a summary of AD DS capabilities. | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/68191814b846196a0190463d8edcac2bdaac953a/image%202.png) |
| 4️⃣   | The wizard confirmed role selections including AD DS. After installation, Server Manager prompted to promote the server to a Domain Controller. | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/030b1d5b31e62522944b8084e685fdb8233e5ac1/image%203.png) |
| 5️⃣   | Used the AD DS Configuration Wizard to promote Windows Server 2022 to a Domain Controller by creating a new forest, setting the domain name (Server.local), defining the DSRM password, selecting functional levels, and configuring DNS. | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/1901968221281fbda80fdcb6b62bc24908d4e61c/image%204.png) |
| 6️⃣   | Final steps before promoting the server to a Domain Controller: set NetBIOS name, configure AD DS paths, review settings, and pass the prerequisites check. Ready for domain setup!   | ![Image Alt](https://github.com/Shaifalim02/Windows_Server_2022/blob/1901968221281fbda80fdcb6b62bc24908d4e61c/image%205.png) |


