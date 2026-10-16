# AZ-802T00 Administer Windows Server - Day 4 Errata
## Finish Learning Path 5: ​Manage storage and file services​​
## Learning Path 6:​  Secure Windows Server​​

## Note: Use PowerShell ISE as a Administrator as direct paste in PowerShell console doesn't work.

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
