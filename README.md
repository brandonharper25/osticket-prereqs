<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Other Notes</h2>

-I used a Macbook M4 Pro for this lab. 

-You can use any operating system you like.

-**Please note that Remote Desktop is called "Windows App" in the macOS App Store**.


<h2>Environments and Technologies Used</h2>

    - Microsoft Azure (Virtual Machines/Compute)
  
    -Windows 10(Virtual Machine)
  
    - Remote Desktop
  
    - Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Preinstallation osTicket files(Download First)</h2>
<p>
    <a href="https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD">
     osTicket-Installation-Files
    </a>
</p>


<h2>List of Prerequisites</h2>

<h3>*Must have an active Microsoft Azure Subscription*</h3>

<h3>Lab Ojectives</h3><br />

- Create Virtual Machine in Mircrosoft Azure
- Install OsTicket
- Install MySQL
- Install HeidiSQL
- Install PHP
- Install Microsoft Visual C++

<h2>Installation Steps</h2>
<p>
Step 1: Log into your Microsoft Azure account. Click on the virtual machine tab and click the + create button to create a virtual machine(VM). 
</p>
<br />
<p>
<img width="2954" height="1518" alt="Create VM" src="https://github.com/user-attachments/assets/2a20e367-a984-473e-8716-f3418c7219f3" />
</p>

<p>
Step 2: 

  - **Create a new resource group:** `osTicket`  

  - **Virtual machine name:** `osticket-vm`  

  - **Select a region:** Any (just remember which one)  

  - **Image:** `Windows 10 Pro, version 22Hz - x64 Gen2`  

  - **Size:** Any (preferably 2/+ CPUs)  

  - **Username and password:** Any (just remember them)
  
  - After that click on the Review + create button and wait for the virtual machine(VM) to set up.  

</p>
<p>
  Step 3: Copy the Public IP address from the VM information page. Make sure you have Remote Desktop for Windows open  or if using a macOS as I was, "Windows App" downloaded from the macOS App store. Once entered into the "Windows App" click on Add PC. Copy the VM's public IP address to the "PC Name" field. Under the "Friendly Name" field type osTicket. Then click the "Add button" to create the osTicket VM. Wait for the osTicket VM to finalize itself. 
</p>
<p>
  Step 4: 
</p>
<img width="3020" height="1876" alt="image" src="https://github.com/user-attachments/assets/f13dc3ea-772c-4443-a190-87128bcdcd57" />
<p>

</p>

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
