<p align="center">
<img src="https://www.msudenver.edu/wp-content/uploads/2025/11/CompTIA-A-Plus_CompTIA-Computing-Technology-Industry-Association_A-Plus-scaled.png" alt="osTicket logo"/>
</p>

<h1>Manage IaaS Virtual Machines (VMs) in Azure That Run Windows Server</h1>
This tutorial outlines Managing IaaS VMs in Azure that run Windows Server<br />

<h2>Environments and Technologies Used</h2>

- CompTIA CertMaster
- Virtual Lab
- Internet Connection

<h2>Operating Systems Used </h2>

- <b>Windows 11 </b> (25H2)

<h2> Troubleshooting Methodology</h2>

1. Identify The Problem

2. Establish A Theory

3. Test Theory

4. Establish A Plan of Action

5. Verify Functionality

6. Document Procedure
   
<h2>Directions</h2>
<h4>"You've received a service request from an employee experiencing a critical issue where their system shuts down unexpectedly before it can fully boot. You believe the power supply unit (PSU) may be at fault. If it does need to be replaced, select one that includes PCIe connectors for future hardware updates. Your task is to test the existing PSU and, if needed, select a compatible replacement that meets both current and future needs."</h4> 

 
 <h3>1. Identify The Problem</h3>
 
  <img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/2f68fbc3-8949-43fa-945f-3d4b99bf431a" />

   Attempted to power on the PC to verify there was no connection. Received "Computer failed to turn on" error message.

 <h3>2. Establish A Theory</h3>

   <img width="850" height="450" alt="Screenshot 2026-04-09 122510" src="https://github.com/user-attachments/assets/9af93654-25a7-49a0-8bc3-cf284bef7d3a" />
  
   Observed the Power supply tester and noticed fluctuating readings with an occasional LL code. The "L" indicates a Low reading, meaning the tester detects voltage below the minimum threshold or a missing signal. This typically points to a fault with the PG (Power Good) signal.

 <h3>3. Test The Theory</h3>

  <img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/c91a924d-0d47-48e0-8636-99df2b24f534" />

  Tested the theory by replacing the PSU and rerunning the Power Supply Tester. Observed stable readings.

  <h3>4. Establish a Plan of Action</h3>

  <img width="850" height="450" alt="Screenshot 2026-04-09 123515" src="https://github.com/user-attachments/assets/d8fd29b5-234f-42c5-98b9-4839e0be92b2" />

   Replaced the power supply unit and reconnected the power cables.

   <h3>5. Verify Functionality</h3>

   <img width="850" height="450" alt="Screenshot 2026-04-09 123615" src="https://github.com/user-attachments/assets/88fc76ac-0cd8-4730-8a8f-08f3a1e48515" />

   Verified the function of the PC by powering on and logging in to the desktop screen.

   <h3>6. Document Procedure</h3>

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
