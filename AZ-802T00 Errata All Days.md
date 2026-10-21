# AZ-802T00 Administer Windows Server - Errata All Learning Paths (All Days)

## Learning Path 1: Deploy and manage Active Directory Domain Services

## Note: Use PowerShell ISE as Administrator since direct paste in PowerShell console doesn't work.

## Lab 01: Implementing identity services and Group Policy (45 Minutes)

### Exercise 1: Deploying a new domain controller on Server Core
Task 1: Deploy AD DS on a new Windows Server Core server <br>
No Errata <br>

Task 2: Prepare the AD DS installation and promote a remote serve <br>
Step 9: Use the Contoso\administrator credential in the lab, located under the resources tab<br>
Step 12: Use the Contoso\administrator password in the lab <br>
Second Step 4: Copy and paste everything into the ISE, then do step 4 <br>
Second Step 7: Paste into the ISE <br>
Second Step 8: Paste the entire line starting with Install-ADDSComainController between the {}, remove any additional spaces at the end <br>
Second Step 9: Press run to invoke the command <br>
Second step 14: Keep the ISE open for the next Task <br>

Task 3: Manage objects in AD DS <br>
The steps may not paste correctly directly into the ISE run pane, paste them into the script pane first, then delete the line and paste the next command
Steps 5 - 9: Does not paste correcty. Use these steps to complete in the Gui > Launch Server Manager > Navigae to Tools > Active directory Users and Computers > Seattle OU > Right click Ty > Reset Password > type Pa55w.rd twice and clear the Check box User must change password at logon > Click OK > Right click on the Ty and select Enable <br>

### Exercise 2: Configuring Group Policy
Task 1: Create and edit a GPO <br>
No errata <br>

Task 2: Link the GPO
No errata <br>

Task 3: Review the effects of the GPO's settings
No errata <br>

Task 4: Create and link the required GPOs
No errata <br>

Task 5: Verify the order of precedence
No errata <br>

Task 6: Configure the scope of a GPO with security filtering
No errata <br>

Task 7: Verify the application of settings
No errata <br>

# Day 2 Errata
## Learning Path 2: Manage Windows Server instances and workloads in a hybrid environment
## Learning Path 3: Manage virtual machines

## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

## Learning Path 2: Manage Windows Server instances and workloads in a hybrid environment (~45 Minutes)
## Lab 02 – Managing Windows Server

### Exercise 1: Implementing and using remote server administration

Ensure you read the note and uninstall Windows Admin Center <br>
Here are the steps to unistall Windows Admin Center <br>
Click Start - Settings <br>
Click Apps <br>
Select Windows Admin Center - Select Uninstall <br>

Task 1: Install Windows Admin Center <br>
Step 4: When the website opens - close it <br>

Task 2: Task 2: Add servers for remote administration <br>
Step 1: Use the instructions provided by the instuctor to launch the wesbite if the certificate is expired. Use the Contoso\administrator credential in the lab, located under the resources tab, select the box Use these credentials for all connections <br
Step 8: If prompted <br>

Task 3: Configure Windows Admin Center extensions <br>
Step 5: Use the drop down arrow <br>

Task 4: Verify remote administration <br>
Ensure the Admin Center is connected to SEA-DC1 <br>
Step 9: Enter the correct password befpre sec;ecting connect <br>

Task 5: Administer servers with Remote PowerShell <br>
No errata <br>

## Learning Path 3: Manage virtual machines
## Lab 03 – Implementing and configuring virtualization in Windows Server (~60 Minutes)

Ensure you read the note and uninstall Windows Admin Center <br>
Here are the steps to unistall Windows Admin Center <br>
Click Start - Settings <br>
Click Apps <br>
Select Windows Admin Center - Select Unistall

### Exercise 1: Creating and configuring VMs
Task 1: Create a Hyper-V virtual switch <br>
Step 4: When the website opens - close it <br>

Task 2: Create a virtual hard disk <br>
No errata <br>

Task 3: Create a virtual machine <br>
Step 6: Set the mmemory to 2048 <br>
Step 14: Set the mmemory to 2048 <br>

Task 4: Manage Virtual Machines using Windows Admin  <br>
Step 8: Use the instructions provided by the instuctor to launch the wesbite if the certificate is expired. Use the Contoso\administrator credential in the lab, located under the resources tab, if available select the box Use these credentials for all connections <br

### Exercise 2: Installing and configuring containers

Task 1: Install Docker on Windows Server <br>
Step 1: Ensure you launch a PS Session with SEA-SVR1 <br>
Step 2: Run the CMDLets seperately <br>
Step 3: Ensure you are in the PS Session on SEA-SVR1 <br>

Task 2: Install and run a Windows container <br>
Step 5: Requires you to be on Sea-SVR1 - Switch to SEA-SVR1 - Logon and exit the SConfig window - Paste does not work - type in manually <br>
Step 9 - 13: Can be ran from the SEA-ADM1 computer <br>

Task 3: Use Windows Admin Center to manage containers
Step 1: If needed launch the Windows Admin Center and enter your credentials - the seetings icon is in the top right corner<br>

# Day 3 Errata

## Learning Path 4 Lab 04: Manage network infrastructure services ~60 Minutes
## Learning Path 5 Lab 05: Implementing Azure File Sync ~60 Minutes
## Keep an eye on the time - the allotted time is 60 minutes, this lab will require extending at least once
## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

## Learning Path 4 Lab: Manage network infrastructure services
## Lab 04: Implementing and configuring network infrastructure services in Windows Server (~60 Minutes)

### Exercise 1: Deploying and configuring DHCP

Ensure you read the note and uninstall Windows Admin Center <br>
Here are the steps to unistall Windows Admin Center <br>
Click Start - Settings <br>
Click Apps <br>
Select Windows Admin Center - Select Uninstall <br>

Task 1: Install the DHCP role
Step 4: When the website opens - close it <br>
Step 8: Use the instructions provided by the instuctor to launch the wesbite if the certificate is expired. Use the Contoso\administrator credential in the lab, located under the resources tab, if available select the box Use these credentials for all connections <br
Step 18: You may not be challenged for credentials <br>
Step 21: Click on notifications to verify DHCP is being installed, keep refreshing the screen until DHCP shows up under Tools - do not continue until done <br>

Task 2: Authorize the DHCP server <br>
No errata <br>

Task 3: Create a scope <br>
No errata <br>

Task 4: Configure DHCP Failover <br>
No Errata <br>

Task 5: Verify DHCP functionality <br>
No errata <br>

### Exercise 2: Deploying and configuring DNS

Task 1: Install the DNS role
No Errata <br>

Task 2: Create a DNS zone
No Errata <br>

Task 3: Configure forwarding
No Errata <br>

Task 4: Configure conditional forwarding
No Errata <br>

Task 5: Configure DNS policies
No Errata <br>

Task 6: Verify DNS policy functionality
No Errata <br>

## Learning Path 5 Lab: Manage storage and file services
## Lab 05: Implementing Azure File Sync ~60 Minutes

### Exercise 1: Implementing Distributed File System (DFS) Replication in your on-premises environment

Task 1: Deploy DFS <br>
No erraa <br>

Task 2: Test DFS deployment
No errata <br>

### Exercise 2: Creating and configuring a sync group

Task 1: Create an Azure file share
No errata <br>

Task 2: Use an Azure file share <br>
No errata <br>

Task 3: Deploy Storage Sync Service and a File Sync group <br>
No errata <br>

### Exercise 3: Replacing DFS Replication with File Sync-based replication

Task 1: Add SEA-SVR1 as a server endpoint <br>
Step 16: May take a few minutes to populate <br>

Task 2: Register SEA-SVR2 with File Sync <br>
No errata <br>

Task 3: Remove DFS Replication and add SEA-SVR2 as a server endpoint <br>
No errata <br>

### Exercise 4: Verifying replication and enabling cloud tiering

Task 1: Verify File Sync <br>
No errata <br>

Task 2: Enable cloud tiering <br>
No errata <br>

### Exercise 5: Troubleshooting replication issues

Task 1: Monitor File Sync replication
No errata <br>

Task 2: Test replication conflict resolution <br>
No errata <br>

### Exercise 6: Cleaning up the Azure subscription

Task 1: Delete the Azure resources that were created in the lab <br>
Step 12; Select Delete sync group from inside of Sync1 <br>

# Day 4 Errata

## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

# AZ-802T00 Administer Windows Server - Day 4 Errata
## Learning Path 5 Lab 6: Implementing storage solutions in Windows Server ~90
## Learning Path 6 Lab 07:​  Secure Windows Server​​ ~45 Minutes

## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

## Learning Path 5 Lab: Manage storage and file services
## Lab 6: Implementing storage solutions in Windows Server
### Exercise 1: Implementing Data Deduplication

Task 1: Install the Data Deduplication role service <br>
Step 16: Pasting into SEA-SVR3 does not work - Open Type notepad by typeing notepad.exe - paste into notepad and then copy into the PowerShell Prompt <br>
Step 17: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>

Task 2: Enable and configure Data Deduplication <br>
No errata <br>

Task 3: Test Data Deduplication <br>
Before starting Task 3 you need to uninstall the existing Windows Admin Center using the following steps <br>
Here are the steps to unistall Windows Admin Center <br>
Click Start - Settings <br>
Click Apps <br>
Select Windows Admin Center - Select Uninstall <br>
Step 3: It will take a few moments for the install to start - be patient. If the Windows Admin Center opens - close it <br>
Step 7: Use the instructions provided by the instuctor to launch the wesbite if the certificate is expired. Use the Contoso\administrator credential in the lab, located under the resources tab, if available select the box Use these credentials for all connections <br
Step 10: Wait for the extensions to finish installing and you get the OK prompt <br>
Step 17: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>

### Exercise 2: Configuring iSCSI storage

Task 1: Install iSCSI and configure targets <br>
Step 4: Paste into the ISE script pane and the use F8 to run each line individually, wait for each to run and complete <br>
Step 5: Paste into the ISE script pane and the use F8 to run each line individually, wait for each to run and complete  <br>
Step 6: Paste into the ISE script pane and the use F8 to run each line individually, wait for each to run and complete  <br>
Step 7: Paste into the ISE script pane (if both comlets paste on 1 line split them between e lines) and the use F8 to run each line individually, wait for each to run and complete  <br>

Task 2: Connect to and configure iSCSI targets <br>
Step 23: Pasting into SEA-DC1 does not work - Open Type notepad by typeing notepad.exe - paste into notepad and then copy into the PowerShell Prompt <br>

Task 3: Verify iSCSI disk configuration <br>
Step 5: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
Step 7: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
Step 8: Pasting into SEA-SVR3 does not work - paste into notepad, make changes and then copy into the PowerShell Prompt - if you see an error ignore as the drive will be formatted <br>

Task 4: Revert disk configuration <br>
Step 2: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>

### Exercise 3: Configuring redundant Storage Spaces

Task 1: Create a storage pool <br>
Step 5: May require refreshing before the disks show online <br>

Task 2: Create a volume based on a three-way mirrored disk <br>
Step 13: The new volume wizard launches automatically <br>

Task 3: Manage a volume in File Explorer <br>
No errata <br>

Task 4: Disconnect a disk from the storage pool and verify volume availability <br>
No errata <br>

Task 5: Add a disk to the storage pool and verify volume availability <br>
No errata <br>

Task 6: Revert disk configuration <br>
Step 2: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>

### Exercise 4: Implementing Storage Spaces Direct

Note: Ensure you exit out of the PSSession with SEA-SVR3 before continueing <br>

Task 1: Prepare for installation of Storage Spaces Direct <br>
No Errata <br>

Task 2: Create and validate a failover cluster <br>
No Errata <br>

Task 3: Enable Storage Spaces Direct
No Errata <br>

Task 4: Create a storage pool, a virtual disk, and a share <br>
Step 7: The shares tab is at the bottom of the page <br>

Task 5: Verify Storage Spaces Direct functionality <br>

## Learning Path 6:​ Secure Windows Server​​
## Lab 07: Configuring security in Windows Server ~45 Minutes

### Exercise 1: Configuring Windows Defender Credential Guard

Task 1: Enable Windows Defender Credential Guard using Group Policy <br>
No Errata <br>

Task 2: Enable Windows Defender Credential Guard using the Hypervisor-Protected Code Integrity (HVCI) and Windows Defender Credential Guard hardware readiness tool <br>
No Errata <br>

### Exercise 2: Locating problematic accounts

Task 1: Locate and reconfigure domain accounts with non-expiring passwords <br>
No Errata <br>

Task 2: Locate and disable domain accounts that have not been used to sign in for at least 90 days <br>
No Errata <br>

### Exercise 3: Implementing LAPS

Task 1: Prepare computer accounts for implementing LAPS (Local Administrator Password Solution) <br>
Step 8: Paste into the Script pane - use F8 to run each line individually <br>

Task 2: Prepare AD DS for LAPS <br>
Step 1: Paste into the Script pane - use F8 to run each line individually <br>

Task 3: Deploy LAPS client-side extension <br>
Step 2: Pasting into SEA-SVR1 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
Step 3: Pasting into SEA-SVR1 does not work - paste into notepad and then copy into the PowerShell Prompt <br>

Task 4: Verify LAPS <br>
No errata <br>

# Day 5 Errata
## Learning Path 8:​ Monitor and troubleshoot Windows Server environments​​

## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

## Lab 08: Monitoring and troubleshooting Windows Server ~60 Minutes

Task 1: Create and start a data collector set <br>
No errata <br>

Task 2: Create a typical workload on the server <br>
No errata <br>

Task 3: Analyze the collected data <br>
No errata <br>

### Exercise 2: Identifying the source of a performance problem

Task 1: Create additional workload on the server <br>
No errata <br>

Task 2: Capture performance data by using a data collector set <br>
No errata <br>

Task 3: Remove the workload and review the performance data <br>
No errata <br>

### Exercise 3: Viewing and configuring centralized event logs

Task 1: Configure subscription prerequisites <br>
No errata <br>

Task 2: Create a subscription and verify the results <br>
No errata <br>
