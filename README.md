<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (25H2)

<h2>List of Prerequisites in 5 Clear Steps</h2>

1. Create and Connect to the Virtual Machine
2. Prepare IIS and PHP Environment
3. Install and Configure MySQL
4. Deploy osTicket
5. Finalize osTicket Setup

<h1>Installation Steps (Images & Explanations)</h1>
<h2>1. Create and Connect to the Virtual Machine</h2>
<p>
<img width="1758" height="1522" alt="image" src="https://github.com/user-attachments/assets/73758918-da31-433c-ba49-0c7543f2aa27" />
</p>
<p>
Description: Configuration of Windows 11 VM created in Microsoft Azure.
</p>
<br />
<img width="2320" height="1422" alt="image" src="https://github.com/user-attachments/assets/6b14bb73-dd5e-4dc6-8e5f-bc8a45c060b9" />
</p>
<p>
Description: Using RDP on MacOS to connect to VM.
</p>
<br />
<img width="1467" height="915" alt="Screenshot 2025-10-28 at 6 31 17 PM" src="https://github.com/user-attachments/assets/30e25c67-538e-4916-8f8a-26ca0353d4c5" />
</p>
<p>
Description: Desktop view of connected VM.
</p>
<br />

<h2>2. Prepare IIS and PHP Environment</h2>
<p>
<img width="2928" height="1826" alt="image" src="https://github.com/user-attachments/assets/1949847d-521b-4bf3-ac37-7c68a563e3de" />
</p>
<p>
Description: Enabling IIS with CGI in Windows Server Manager.
</p>
<br />
<p>
<img width="2420" height="1366" alt="image" src="https://github.com/user-attachments/assets/c393358e-9b04-48f5-8389-658ca9018b3c" />
</p>
<p>
Description: Installing PHP Manager for IIS.
</p>
<br />
<p>
<img width="2454" height="1332" alt="image" src="https://github.com/user-attachments/assets/98f93031-a532-4a7f-90f7-bd371fe8e312" />
</p>
<p>
Description: Installing IIS Rewrite Module.
</p>
<br />
<p>
<img width="2350" height="1358" alt="image" src="https://github.com/user-attachments/assets/86792e07-15ef-447a-af90-927263e0779b" />
</p>
<p>
Description: Installing VC_redist.x86.exe.
</p>
<br />

<h2>3. Install and Configure MySQL</h2>
<p>
<img width="2436" height="1372" alt="image" src="https://github.com/user-attachments/assets/b1d16a99-0023-4be4-a816-ad361f374c9d" />
</p>
<p>
Description: Installing MySQL 5.5.62.
</p>
<br />
<p>
<img width="2386" height="1346" alt="image" src="https://github.com/user-attachments/assets/2c0d2159-d623-4d20-93c0-83118789dad3" />
</p>
<p>
Description: Installing HeidiSQL.
</p>
<br />
<p>
<img width="2374" height="1320" alt="image" src="https://github.com/user-attachments/assets/a4e8c178-bcb2-4c17-a9ab-8027dc950a90" />
</p>
<p>
Description: Creating osTicket database.
</p>
<br />

<h2>4. Deploy osTicket</h2>
<p>
<img width="2576" height="1486" alt="image" src="https://github.com/user-attachments/assets/e7bc7213-2820-4a50-9409-e894ee71ceaa" />
</p>
<p>
Description: Registering PHP through PHP Manager in IIS.
</p>
<br />
<p>
<img width="2396" height="1598" alt="image" src="https://github.com/user-attachments/assets/8bdba5d9-28b2-422a-bf89-8b0db8e9bb76" />
</p>
<p>
Description: Enabling necessary PHP extensions via PHP Manager.
</p>
<br />
<p>
<img width="2166" height="1404" alt="image" src="https://github.com/user-attachments/assets/276454fc-74db-4bb3-97b5-a03cf3e13953" />
</p>
<p>
Description: Setting file permissions to "Everyone" with "Full Control" through the Security Settings of the configuration file.
</p>
<br />

<h2>5. Finalize osTicket Setup</h2>
<p>
<img width="2910" height="1734" alt="image" src="https://github.com/user-attachments/assets/8e76d4ba-513c-4925-8a25-cafa3b787fec" />
</p>
<p>
Description: Officially installing osTicket.
</p>
<br />
<p>
<img width="1934" height="1474" alt="image" src="https://github.com/user-attachments/assets/584d3cb0-0614-4b51-aed0-9c114d7c31e5" />
</p>
<p>
Description: Installation successful!
</p>
<br />
<p>
<img width="2934" height="1754" alt="image" src="https://github.com/user-attachments/assets/b0e85fb3-f497-442f-bfe2-62f3389b5a06" />
</p>
<p>
Description: Confirming access as an admin.
</p>
<br />
<p>
<img width="2884" height="1588" alt="image" src="https://github.com/user-attachments/assets/67fffd7a-035e-424c-adc8-b815f73a1e5d" />
</p>
<p>
Description: Confirming access as an end-user.
</p>
<br />

<h1>Final Result:</h1>
<h2>osTicket v1.15.8 successfully installed on a Windows 11 Azure VM with a fully functional IIS, PHP, and MySQL stack.</h2>
