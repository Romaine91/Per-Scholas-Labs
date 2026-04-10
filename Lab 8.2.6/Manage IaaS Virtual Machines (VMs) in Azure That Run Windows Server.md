<p align="center">
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/8473599d-5e56-4f65-b929-1f7de9c2107e" />


<h1>Manage IaaS Virtual Machines (VMs) in Azure That Run Windows Server</h1>
This tutorial outlines Managing IaaS VMs in Azure that run Windows Server.<br />

<h2>Environments and Technologies Used</h2>

- CompTIA CertMaster
- Virtual Lab
- Microsoft Azure
- Internet Connection

<h2>Operating Systems Used </h2>

- <b>Windows 11 </b> (21H2)

<h2>Deployment and Configuration Steps</h2>

1. Created A Virtual Machine

2. Configured VM Details 

3. Configured VM Disks

4. Review Configuration 

5. Verify Deployment Completed

   
<h2>Directions</h2>
"You are the network administrator for your company. You have decided to begin the configuration of Azure to help manage your network. As part of this setup, you need to create a virtual server in Azure."

 
 <h3>1. Created A Virtual Machine</h3>
 
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/956b5c01-ef2d-40e9-bcbe-535e56941da7" />

Within the "Virtual Machine" tab, create a new VM with "Azure virtual machine".

 <h3>2. Configured VM Details</h3>

<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/147b8295-aad6-4b04-9f5d-42a95800abbf" />

<ul>
<li>Virtual machine type: Azure virtual machine</li>
<li>Project details:</li>
 <ul>
  <li>Subscription name: CorpNet Production</li>
  <li>Resource group name: CorpNetCloud</li>
  </ul>
<li>Instance details:</li>
  <ul>
   <li>Virtual machine name: CorpCloud1</li>
   <li>Region: (US) West US2</li>
   <li>Image: Windows Server 2022 Datacenter: Azure Edition - Gen2</li>
   <li>Size: Standard_D4s_v3 - 4 vcpu, 16 GiB memory ($327.04/month)</li>
  </ul>
<li>Administrator account:</li>
   <ul>
      <li>Username: CorpAdmin</li>
      <li>Password: corpP@ssw0rd</li>
   </ul>
</ul>

 <h3>3. Configured VM Disks</h3>

<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/a7990b24-7ea5-4045-bdcd-d8c485507912" />

 <ul>
    <li>Disk options:</li>
       <ul>
          <li>Set Standard HDD as the OS disk type.</li>
          <li>Make sure that the Delete with VM box is selected.</li>
       </ul>
    <li>Use the default network parameters.</li>
 </ul>

  <h3>4. Review Configuration</h3>
  
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/9a6dde3b-57cd-410c-ad5a-3af11dfc4982" />

   Review the configuration information for the new VM, as well as the price.

   <h3>5. Verify Deployment Completed</h3>

   <img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/5e81d560-3e0a-450c-ae58-7f638eddc3cf" />

   Verify the VM deployed successfully. A "Deployment succeeded" notification will appear in the top right corner.
