# AZ-802T00 Day 3 Errata
## Learning Path 4 Lab: Manage network infrastructure services
## Learning Path 5 Lab 06: Manage storage and file services

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
## Lab 6: Implementing storage solutions in Windows Server

### Exercise 1: Implementing Data Deduplication

Task 1: Install the Data Deduplication role service <br>
Step 14: Pasting into SEA-SVR3 does not work in the next step - Open PowerShell ISE on SEA-ADM1 and  create a PSSession with SEA-SVR3 <br>
Step 15: Skip <br>
Step 16: Paste into the script pane in the ISE - run each line individually (Place cursor at the beginning of the line press F8) <br>
Step 17: Does not work in a PSSession you will need to run the commands individually on SEA-SVR3 - The 6th command should be just Get-Childitem

Task 2: Enable and configure Data Deduplication <br>
No errata <br>

Task 3: Test Data Deduplication <br>
Step 3: If the Admin Center opens close it. 


