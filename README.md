# Virtual Private Network (VPN)
<p align="center">
<img src="https://github.com/user-attachments/assets/b86d9ed1-874f-4287-bfc0-a82b214e1f78" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial covers the prerequisites and installation process for setting up and using a VPN..<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<p>
Create a Resource Group in Azure, then deploy a Windows 10 Virtual Machine within it. Once the VM is set up, use Remote Desktop Protocol to log into the VM. <br /> <br />
<img src="https://github.com/user-attachments/assets/a5a45a3b-0399-48d2-8392-04498148c9da" height="80%" width="80%"/> <br /> <br />
</p>
<br />

<p>
Once inside the VM, open a web browser and navigate to https://whatismyipaddress.com/. View the IP information displayed and record it in Notepad or on a piece of paper for later reference. <br /> <br />
<img src="https://github.com/user-attachments/assets/ef617472-fca1-4d20-8d42-1375687ae9d6" height="80%" width="80%"/> <br /> <br />
</p>
<br />


<p>
Sign up for the free version of Proton VPN at https://account.protonvpn.com/signup?plan=free&language=en.
Inside the VM, download and install the Proton VPN client. Log in to the client using your Proton VPN credentials at 
https://account.protonvpn.com/login <br /> <br />
<img src="https://i.imgur.com/fUjDc38.png" height="80%" width="80%"/> <br /> <br />
</p>
<br />

<p>
Sign in to the Proton VPN client using the credentials you created during account setup. Once logged in, click "Quick Connect" to connect automatically to a VPN server. Connecting to the VPN will mask your real IP address and encrypt your internet traffic, enhancing privacy and security. <br /> <br />
<img src="https://github.com/user-attachments/assets/52ce5022-20d9-4e41-b80a-5d065f5b2c1b" height="80%" width="80%" /> <br /> <br />
<img src="https://github.com/user-attachments/assets/fa3eefa6-4e48-4fef-9621-23e11b32772c" height="80%" width="80%" /> <br /> <br />
</p>
<br />

<p>
Revisit https://whatismyipaddress.com/ and observe the changes in the IP information. Note how the IP now reflects the VPN server you connected to, demonstrating the VPN's effect. <br /> <br />
<img src="https://github.com/user-attachments/assets/fee921ef-ba67-4607-9f93-6e1b5ec71249" height="80%" width="80%" />
</p>
<br />
