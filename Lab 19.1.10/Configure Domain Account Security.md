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
<!-- <h4>"Insert lab directions here."</h4> -->

 
 <h3>1. Identify The Problem</h3>
 
<!-- Insert Image #1 here.

   Explain Step #1 -->

 <h3>2. Establish A Theory</h3>

<!-- Insert Image #2 />
  
   Explain Step #2 -->

 <h3>3. Test The Theory</h3>

<!-- Insert Image #3
  Explain Step #3 -->

  <h3>4. Establish a Plan of Action</h3>

<!-- Insert Image #4 />

   Explain Step #4 -->

   <h3>5. Verify Functionality</h3>

   <!-- Insert Image #5
   Explain Step #5 -->

   <h3>6. Document Procedure</h3>
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
  Lab 19.1.10



TASK: Configure domain account security
Complete the following work order to add a new Active Directory user:


User name 	Dakota
Password 	Pa55w0rd!
Workstation restriction 	PC machine only
Logon hours restriction 	Mon-Fri 8am-6pm
OU 	Nonadmins
Security group 	sec-glo-sales


Use the following accounts to access machines and services on the local network that might be relevant to resolving the issue.
    Host 	User 	Password
  ADMIN 	Bobby 	Pa55w0rd!

Choose guided steps and hints- HOLD Ctrl and use mouse wheel outside working window in lab to adjust magnification?

You can work independently to complete the task or you can choose to show guided steps and hints. You can only achieve the maximum score if you keep hints hidden.
Check your work

Verify that you have completed the required tasks:
Use Active Directory Users and Computers to verify the account properties.
When you have checked your work, select the Evaluate button to assess and score the task:
	Use Active Directory Users and Computers to verify the account properties.
1.Logged into Bobby on ADMIN to access If necessary, select ADMIN, and sign in as Bobby with Pa55w0rd!

From the Start menu, select Windows Administrative Tools, and then Active Directory Users and Computers.

Expand the domain, and then right-click Nonadmins, and select New, and then User. Complete the wizard by using the following properties:

    Name: Dakota

    Password: Pa55w0rd!

    User must change password: Uncheck

Select Nonadmins. Right-click Daktota, and select Add to a group. Enter sec-glo-sales, and confirm the dialogs.
Right-click Daktota, and select Properties. Select the Account tab.
Click the Log On To button. Select The following computers, and add PC to the list. Select OK.
Click the Log Hours button. Select all the slots, and then select Logon Denied. Select the block of slots representing Mon-Fri 8am-6pm, and select Logon Permitted. Click OK.
Select OK.



Right click in white space to create new user in NonAdmins








TASK: Report group policy
If necessary, select ADMIN, and sign in as Bobby with Pa55w0rd!

From the Start menu, select Windows Administrative Tools, and then Group Policy Management.

Expand the Domains folder, and then expand the domain (ad.structureality.com). Select Group Policy Objects.

This shows all the policies that have been created.

Expand Servers. Observe that a single policy is linked to this object. This means that the policy is applied to objects within the Servers Organizational Unit only.

Observe the link shortcuts attached directly to ad.structureality.com. Record these three policies as the ones that are applied at domain level.

Screenshot of group policy management showing policies linked at domain level as c c domain default default domain policy and u u domain default

Account policies can only be set once per domain, so you only need to examine the Default Domain Policy to report the remaining policy configurations.

In the navigation pane, select Default Domain Policy. In the main pane, select the Settings tab.

Expand Security Settings, then Account Policies/Password Policy. Record the password length and complexity policy configurations.

Expand Account Policies/Account Lockout Policy. Observe that the threshold is zero, so the policy is effectively disabled.







TASK: Configure group policy



If necesssary, select ADMIN, and sign in as Bobby with Pa55w0rd!
If necessary, from the Start menu, select Windows Administrative Tools, and then Group Policy Management.
Expand Group Policy Objects. Right-click cc-servers-adminpolicy, and select Edit.
Under Computer Configuration, expand Policies, then Windows Settings. Expand Security Settings, and then Local Policies. Select User Rights Assignment.
In the main pane, open Allow log on locally.
Check Define these policy settings. Select the Add user or group button.
In the dialog, type Administrators, and select OK. Select OK.
Select MS, and sign in as Bobby with Pa55w0rd!
Right-click Start, and select Run. Type gpupdate, and press ENTER.
When the update is complete, right-click Start, and select Shut down or sign out, and then Sign out.








   <li>Select a power supply from the inventory that has the same 20+4 and 4-pin connectors and the 6-pin PCIe connectors.</li>
   <li>Reconnect the <b>Connector, Power Supply, 20+4 pin</b> and <b>Connector, Power Supply, 4-pin</b> to the motherboard and <b>Connector, SATA 15-pin</b> to each drive.</li>
  </ol>
<li>Plug the computer in, turn on the power supply, and then start the computer.</li>
</ul>
-->
