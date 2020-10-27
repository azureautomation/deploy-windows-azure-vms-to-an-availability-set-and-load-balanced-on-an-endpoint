Deploy Windows Azure VMs to an Availability Set and Load Balanced on an Endpoint
================================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Deploy a specified number of Virtual Machines based on a given image name. The Virtual Machines are placed in the same availability set and load balanced on a given endpoint name.


If the cloud service name already exists, then subsequent call will adds new Virtual Machine instances.

Example
 
Scenario
You need to create a farm of Virtual Machines using a standard disk image and have all instances load balanced.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  Get-AzureVMImage 
  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
