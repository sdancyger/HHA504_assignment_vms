# HHA504_assignment_vms
Assignment for HHA 504

## *Objective*

The objective of this assignment is to provide hands-on experience with managing Virtual Machines (VMs) in both Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor the costs associated with running VMs on these cloud platforms.

# *1. Start and Stop a Virtual Machine*

## Google Cloud Platform (GCP)

The steps I took to start and stop the Virtual Machine within Google Cloud Platform include: 

    1. Opening GCP dashboard.
    
    2. Clicking on "VM instances" under the tab called "Virtual Machines."

    3. Created a new instance with the Virtual Machine name, "virtual-machine-1."

    4. Adjusted the region to "us-east4 (Northern Virginia)."

    5. Confirmed "Machine Configuration/Machine Type" was under "E2-medium."

    6. Ensured settings were "standard/basic."

    7. Created virtual machine.

    8. Allowed new virtual machine to run for a few minutes. 

    9. Stopped virtual machine by clicking the hamburger button bar adjacent to the Virtual Machine instance named, "virtual-machine-1."

![VM Configuration](./GCP%20pictures/GCP%20New%20VM%20Machine%20configuration.png)



![Picture of machine type](<GCP New VM Machine type.png>)

![Boot disc picture](<GCP pictures/GCP New VM Boot disc.png>)

![Instance complete](<GCP pictures/GCP New VM instance complete.png>)

![VMPicture1](<GCP pictures/GCPVM1.png>)

![VMPicture2](<GCP pictures/GCPVM2.png>)

![VMPicture3](<GCP pictures/GCPVM3.png>)

![VMPicture4](<GCP pictures/GCPVM4.png>)

![VMPicture5](<GCP pictures/GCPVM5.png>)

![Stopped VM](<GCP pictures/GCPVM stopped.png>)


## Microsoft Azure

The steps I took to create a Virtual Machine in Microsoft Azure are as follows: 
   
    1. Opening Microsoft Azure platform.
    
    2. Clicking on the "Add a Resource" icon located on the dashboard.

    3. Clicking on "Create a Machine" 

    4. Named virtual machine "virtual-machine-1"

    5. Ensured region "US East" was present. 

    6. Ensured Ubuntu Server was present for image settings.

    7. Ensured basic configuration was present, and "Size" of "Standard_DC1s_v2- 1 vcpu, 4 GiB memory ($0.01162/hr).

    8. Allowed Virtual Machine to run for a few minutes.

    8. Stopped Virtual Machine named, "virtual-machine-1."

![CreateVMAzure](<GCP pictures/Azurecreatevm.png>)

![Pic1Azure](<GCP pictures/Azurepic1.png>)

![Passed validation VM Azure](<GCP pictures/Azurepassedvalidation.png>)


    My Azure Virtual Machine named "virtual-machine-1" passed validation and then proceeded to the "Deployment" phase. 
    
    After the deployment phase completed, I was able to review my Virtual Machine. 

![Deployment of VM Azure](<GCP pictures/Azuredeployment.png>)

![Deployment of VM Azure complete](<GCP pictures/Azuredeploymentcomplete.png>)

    Review of Virtual Machine

![overview 1 VM](<GCP pictures/AzureVMoverview1.png>)

![overview 2 VM](<GCP pictures/AzureVM overview2.png>)

![Azure VM activity log](<GCP pictures/AzureVMactivitylog.png>)

    Stopping of Virtual Machine

![Azure VM stopped](<GCP pictures/AzureVMstopped.png>)


# *2. Monitor VM Costs*

## Google Cloud Platform (GCP)

    I was able to review and monitor the costs for GCP by accessing the "Billing" section of GCP. I navigated towards:
        
        1- "Billing Overview" 
        2- "Billing Reports"
        3- "Billing Cost Table"
        4- "Billing Cost Breakdown"
    
There were no costs recorded at this time. There were no costs due to the VM not being able to run for a sufficient amount of time to aquire such costs. However, if the VM ran for an extended period of time, the charges would be able to be easily viewed under "Cost Breakdown."

![Main billing](<GCP pictures/GCPbillingmain.png>)
        
![Overview billing](<GCP pictures/GCPbillingoverview.png>)

![Reports billing](<GCP pictures/GCPbillingreports.png>)

![Cost table billing](<GCP pictures/GCPbillingcosttable.png>)

![Cost breakdown billing](<GCP pictures/GCPbillingcostbreakdown.png>)


## Microsoft Azure

  I was able to review and monitor the costs for Microsoft Azure by accessing the "Cost Management" and "Billing" tabs in Microsoft Azure. 
  
  I navigated towards:
        
        Cost Management
        1- "Cost Analysis" 
        2- "Cost Alerts"
        3- "Budgets"
        4- "Advisor Recommendations"

        Billing
        1- "Invoices"
        2- "Payment methods"
        3- "Payment history"
        4- "Billing Profiles"
        5- "Benefits (preview)


![cost analysis](<GCP pictures/Azurecostmgmtcostanalysis.png>)

![Cost alert](<GCP pictures/Azurecostmgmtcostalert.png>)

![Budget](<GCP pictures/Azurecostmgmtbudget.png>)

![advisement](<GCP pictures/Azurecostmgmtadvisement.png>)

![billing invoice](<GCP pictures/Azurebillinginvoice.png>)

![payment method](<GCP pictures/Azurebillingpaymentmethod.png>)

![payment history](<GCP pictures/Azurebillingpaymenthistory.png>)

![billing profile](<GCP pictures/Azurebillingprofile.png>)

![benefits](<GCP pictures/Azurebillingbenefits.png>)


# *3. Compare and Reflect*

I found the Google Cloud Platform (GCP) very easy and clear to nagivate. I was able to successfully create, run, and stop my virtual machine instance named "virtual-machine-1." All of the features to review costs and billing management were working, however no data was available due to the short run-time of the virtual machine. GCP provided a cost of $0.04/hr, with a monthly estimate of $28.65/mo. 

I was able to run my virtual machine named "virtual-machine-1" on Microsoft Azure as well. The virtual machine "Cost Management" and "Invoices" tabs did not have any numerical data as the Virtual Machine was not running for an adequate amount of time to incur costs. If the Virtual Machine remained running, costs would eventually be able to reviewed and analyzed in these tabs. Microsoft Azure provided a cost of $0.0116/hr.

Microsoft Azure's hourly cost was less than Google Cloud Platform's (GCP) hourly cost. I found it easier to navigate, utilize, create, edit, and stop the Virtual Machine in GCP compared to Microsoft Azure. Due to GCP's more user-friendly design platform, I prefer it's use compared to Microsoft Azure. 