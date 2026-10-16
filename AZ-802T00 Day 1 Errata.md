# AZ-802T00 Administer Windows Server - Day One Errata
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