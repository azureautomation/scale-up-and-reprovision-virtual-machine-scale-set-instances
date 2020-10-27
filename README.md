Scale Up and Reprovision Virtual Machine Scale Set Instances
============================================================

            

This Azure Automation runbook will scale up and reprovision Virtual Machine Scale Set instances. This is intended to run only in Azure Automation service. An Azure Automation account with the 'Run as' feature is required. Read more about the 'Run as' feature
 here 
https://azure.microsoft.com/en-us/documentation/articles/automation-sec-configure-azure-runas-account/



NOTE: Reprovisioning actually deletes existing instances and creates newer bigger sized ones. If you do not want this behavior, use the other vertical scale runbooks.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
