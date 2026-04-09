<p align="center">
<img width="250" height="250" src="https://www.startpage.com/av/proxy-image?piurl=https%3A%2F%2Fhurbad.com%2Fwp-content%2Fuploads%2F2021%2F12%2FCisco-Packet-Tracer.png&sp=1775764871T8f4b04143804874cc5528eb70c99a21b9f83ea76432f774358d69982a4a62e9b" alt="osTicket logo"/>
</p>

<h1> ACL Demonstration</h1>
This tutorial outlines Access Control List configuration<br />

<h2>Environments and Technologies Used</h2>

- Cisco Packet Tracer
- ACL Demonstration.pka
- Internet Connection

<h2>Operating Systems Used </h2>

- <b>Windows 11</b> (25H2)

<h2> Troubleshooting Methodology</h2>

1. Identify The Problem

2. Establish A Theory

3. Test Theory

4. Establish A Plan of Action

5. Verify Functionality

6. Document Procedure
   
<h2>Directions</h2>
<h4>"In this activity, you will observe how an access control list (ACL) can be used to prevent a ping from reaching hosts on remote networks. After removing the ACL from the configuration, the pings will be successful."</h4>

 <h3>1. Identify The Problem</h3>
 
  <img width="850" height="450" alt="Screenshot 2026-04-09 154352" src="https://github.com/user-attachments/assets/455829e5-bd91-46f6-8f12-c9598bac9c31" />

   Pinged PC2 and PC3 from PC1 to test connectivitiy to devices within local network router.

 <h3>2. Establish A Theory</h3>

   <img width="850" height="450" alt="Screenshot 2026-04-09 154642" src="https://github.com/user-attachments/assets/2e50d844-02cf-450f-80fc-2c6b2ce20844" />

   Pinged PC4 from PC1 to test connectivity to devices outside of PC's router network. PC1 was unable to ping PC4.

 <h3>3. Test The Theory</h3>

 <img width="850" height="450" alt="Screenshot 2026-04-09 155124" src="https://github.com/user-attachments/assets/49d5089f-af7f-45b7-b573-315004b63a8e" />

  Viewed router 1 (R1) configuration and access-list configuration. PC1's IP address is being blocked by the router and is unable to send traffic outside of the local network.

  <h3>4. Establish a Plan of Action</h3>

  <img width="850" height="450" alt="Screenshot 2026-04-09 155651" src="https://github.com/user-attachments/assets/6bc0b028-3ec6-4db3-a79e-1a9c76586e07" />

   Changed R1's configurationd and access list configuration to allow PC1 to send traffic outside of the local network.

   <h3>5. Verify Functionality</h3>

   <img width="850" height="450" alt="Screenshot 2026-04-09 155845" src="https://github.com/user-attachments/assets/6123fea3-5824-4c76-853a-3feaa07dd407" />
   
   Verified PC1 is able to ping PC4 and DNS Server.

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
