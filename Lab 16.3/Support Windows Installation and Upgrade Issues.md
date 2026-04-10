<p align="center">
<img src="https://www.msudenver.edu/wp-content/uploads/2025/11/CompTIA-A-Plus_CompTIA-Computing-Technology-Industry-Association_A-Plus-scaled.png" alt="osTicket logo"/>
</p>

<h1>Support Windows Installation and Upgrade Issues</h1>
This tutorial outlines the installation of Windows and solving upgrade issues.<br />

<h2>Environments and Technologies Used</h2>

- CompTIA CertMaster
- Virtual Lab
- Internet Connection

<h2>Operating Systems Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Windows 11</b> (25H2)

<h2>Tasks:</h2>

1. Perform in-place Upgrade

2. Resolve Boot Issue

<h2>Task #1 Directions</h2>
"Perform an in-place upgrade on HOMEPC to install Windows 11 Pro.
Verify whether a hardware upgrade is required:

<ul>
   <li>If the hardware must be upgraded, perform the installation on HOMEPC (UPGRADED)</li>
   <li>If the current hardware meets the requirements for Windows 11, perform the installation on HOMEPC</li>
</ul>

Use the following accounts to access machines and services on the local network that might be relevant to resolving the issue."

<table>
  <tr>
    <th>Host</th>
    <th>User</th>
    <th>Password</th>
  </tr>
  <tr>
    <td>HOMEPC</td>
    <td>Sam</td>
    <td>Pa55w0rd!</td>
  </tr>
  <tr>
    <td>HOMEPC (UPGRADED)</td>
    <td>Sam</td>
    <td>Pa55w0rd!</td>
  </tr>
</table>
 
 <h3>1. Mount "Windows 11" installation DVD</h3>
 
<img width="850" height="450" alt="Screenshot 2026-04-10 144939" src="https://github.com/user-attachments/assets/e4c55d03-ba55-4d5e-beb0-f2f10d67d284" />

Power on the computer and insert the Windows 11 installation disk into the disk drive. Then, log in to the PC using Sam's account. Navigate to the File Explorer, then This PC, and finally the D: drive.

 <h3>2. Run "setup" Application</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 145823" src="https://github.com/user-attachments/assets/7fbaebdc-c7a2-439d-9825-c8b3f8dcea9b" />

Click the setup application within the D: and proceed through the wizard prompts. On the HOMEPC, the machine does not meet the requirements for Windows 11. On the HOMEPC (UPGRADED) machine, click Install.

 <h3>3. Allow Windows 11 to Install</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 152636" src="https://github.com/user-attachments/assets/b3e45472-3b09-4cc4-b580-ce61177c4428" />

Allow the machine to install Windows 11. The install will restart the machine a few times during the process. When the machine has finished updating, log in as Sam to finish the process.

  <h3>4. Verify the Install was Successful</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 154052" src="https://github.com/user-attachments/assets/9039f5d5-bfd3-41e8-9e10-54413a5b2c04" />

While signed in as Sam, navigate to Run by either using Win+R, right clicking the Start Menu and selecting Run from the list, or searching for Run in the search menu. Use the command "winver" to verify the Windows version of the machine is now Windows 11.

<h2>Task #2 Directions</h2>
"While you were performing the upgrade on HOMEPC, Sam reports a sudden problem with the LAPTOP machine and that "Nothing seems to work." You consult your system notes, and learn that an image backup was made of this machine and is stored on a local disk separate from the system disk, but no current data backup is available. Diagnose and resolve the issue.

Use the following accounts to access machines and services on the local network that might be relevant to resolving the issue."

<table>
  <tr>
    <th>Host</th>
    <th>User</th>
    <th>Password</th>
  </tr>
  <tr>
    <td>LAPTOP</td>
    <td>Sam</td>
    <td>Pa55w0rd!</td>
  </tr>
</table>

<h3>1. Attempt to Boot Up Laptop</h3>
 
<img width="850" height="450" alt="Screenshot 2026-04-10 154508" src="https://github.com/user-attachments/assets/ff8583d2-fbd5-4d70-8334-bbab4a63ebcc" />

Attempt to log in as Sam and observe the machine is unable to start. The machine attempts to repair, but is unsuccessful. Select "Advanced options".

 <h3>2. Navigate to Troubleshoot</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 154742" src="https://github.com/user-attachments/assets/eedb24fe-598e-4d3c-b2d3-2e7ce59fb24d" />

In the "Choose an Option" menu, select "Troubleshoot". Selected "Advanced options", then "See more recovery options". Finally, select "System Image Recovery".

 <h3>3. Re-Image Computer</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 154846" src="https://github.com/user-attachments/assets/bb48f2a0-17e7-47f4-a8c3-c07f90d31b44" />

In the "Re-image your computer" wizard, select "Use the latest available system image". The location of this backup will be within the D: drive named BACKUP. Click next. Then, click next again on the "Choose additional restore options" menu. Select "Yes" if prompted, then select "Finish".

  <h3>4. Allow System to Re-Image</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 155313" src="https://github.com/user-attachments/assets/7c710f38-a271-4f1b-aa82-505201f85722" />

The machine will now restore back to the latest backup image. When the process has completed, log into the machine as Sam, then navigate to File Explorer, then the Documents tab.

 <h3>4. Verify WEBSITE PROJECT was Restored</h3>

<img width="850" height="450" alt="Screenshot 2026-04-10 155528" src="https://github.com/user-attachments/assets/ca26045f-af21-4233-981e-f04deed7abe7" />

Within the Documents tab, Sam should now have access to their folder, "WEBSITE PROJECT".
