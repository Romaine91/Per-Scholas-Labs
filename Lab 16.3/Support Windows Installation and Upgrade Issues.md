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
<!-- <h4>"Insert lab directions here."</h4> -->
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

<!--
<ul>
<li>Attempt to boot the computer to verify the issue, and then complete these steps:</li>
 <ul>
  <li>Place the <b>Power Supply Tester</b> on the workbench.</li>
  <li>Unplug the computer.</li>
  <li>Disconnect power to internal hard drives.</li>
  </ul>
<li>Test the power supply.</li>
  <ul>
   <li>Transfer the <b>Connector, Power Supply, 20+4 pin</b>, and <b>Connector, Power Supply, 4-pin processor</b> to the power supply tester.</li>
   <li>Attach a <b>Connector, SATA 15-pin</b> power connector to the power supply tester.</li>
   <li>Plug the computer in and view the Power Supply Tester results.</li>
  </ul>
<li>Unplug the power cable from the computer and move the bad power supply to the workbench next to the tester. Leave the cables connected to the tester.</li>
<li>Select and install a new power supply:</li>
  <ol type="a">
   <li>Select a power supply from the inventory that has the same 20+4 and 4-pin connectors and the 6-pin PCIe connectors.</li>
   <li>Reconnect the <b>Connector, Power Supply, 20+4 pin</b> and <b>Connector, Power Supply, 4-pin</b> to the motherboard and <b>Connector, SATA 15-pin</b> to each drive.</li>
  </ol>
<li>Plug the computer in, turn on the power supply, and then start the computer.</li>
</ul>
-->
