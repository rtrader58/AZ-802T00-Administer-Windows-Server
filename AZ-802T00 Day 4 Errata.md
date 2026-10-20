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
