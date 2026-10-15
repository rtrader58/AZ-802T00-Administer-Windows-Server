# AZ-802T00 Day 3 Errata
## Learning Path 4 Lab: Manage network infrastructure services
## Learning Path 5 Lab 06: Manage storage and file services
## Keep an eye on the time - the allotted time is 60 minutes, this lab will require extending at least once
## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

## Learning Path 4 Lab: Manage network infrastructure services
## Lab 04: Implementing and configuring network infrastructure services in Windows Server (~90 Minutes)

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
Step 4: Paste into the ISE script pane and the use F8 to run each line individually <br>
Step 5: Paste into the ISE script pane and the use F8 to run each line individually <br>
Step 6: Paste into the ISE script pane and the use F8 to run each line individually <br>
Step 7: Paste into the ISE script pane and the use F8 to run each line individually <br>

Task 2: Connect to and configure iSCSI targets <br>
Step 23: Pasting into SEA-DC1 does not work - Open Type notepad by typeing notepad.exe - paste into notepad and then copy into the PowerShell Prompt <br>

Task 3: Verify iSCSI disk configuration <br>
Step 5: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
Step 7: Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
Step 8: Pasting into SEA-SVR3 does not work - paste into notepad, make changes and then copy into the PowerShell Prompt - if you see an error ignore as the drive will be formatted <br>

Task 4: Revert disk configuration <br>
No errata <br>

### Exercise 3: Configuring redundant Storage Spaces

Task 1: Create a storage pool <br>
Step 5: May require refreshing before the disks show online <br>

Task 2: Create a volume based on a three-way mirrored disk <br>
No errata <br>

Task 3: Manage a volume in File Explorer <br>
No errata <br>

Task 4: Disconnect a disk from the storage pool and verify volume availability <br>
No errata <br>

Task 5: Add a disk to the storage pool and verify volume availability <br>
No errata <br>

Task 6: Revert disk configuration <br>
No errata <br>

Step 2 Pasting into SEA-SVR3 does not work - paste into notepad and then copy into the PowerShell Prompt <br>
No errata <br>

### Exercise 4: Implementing Storage Spaces Direct

Note: Ensure you exit out of the PSSession with SEA-SVR3 before continueing <br>

Task 1: Prepare for installation of Storage Spaces Direct <br>
