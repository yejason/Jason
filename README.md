# Jason
#this azure json template used to create a vmss with custom image, and the auto scale settings.
# metricTrigger is "Percentage CPU", 
#  "threshold": 60.0 and  "threshold": 30.0
#
# we can use powershell to deploy it, we should create a new group in azure, then use this PowerShell script to deploy it:
# New-AzureRmResourceGroupDeployment -Name ExampleDeployment -ResourceGroupName ExampleResourceGroup -TemplateFile c:\Users\Desktop\jasontest2.json
# 
