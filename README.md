Azure Analysis Services: Backup
===============================

            

Backup-AnalysisServices is a simple PowerShell workflow runbook that will help you automate the process of backing up an Azure Analysis Service Database. 


The script receives 5 parameters:


**ResourceGroupName**: The name of the resource group where the cluster resides         


**AutomationCredentialName**: The Automation credential holding username and password for Analysis Services


**AnalysisServiceDatabase**: The Analysis Service Database


**AnalysisServiceServer**: The Analysis Service Server (i.e. asazure://northeurope.asazure.windows.net/myanalysisservice)


**ConnectionName**: The name of your automation connection account. Defaults to  'AzureRunAsConnection'


 

 

 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
