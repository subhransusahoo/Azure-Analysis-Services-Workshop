# Connect Azure Analysis Services with Tableau Desktop

***






Assumption:
* Exists an Azure Analysis Services Server
* Exists a sample model on that server
* Exists Tableau Desktop Professional Edition 2018.3 (64-bit)
* (Optional) Exists Tableau Desktop Professional Edition 10.4 (32-bit)

***

STEPS:



* Install and/or verify Client libraries. Click on Connection Strings under Settings section. Hover over "i" icon of Provider and Click on the blue link.
<img src="https://github.com/subhransusahoo/Azure-Analysis-Services-Workshop/blob/master/images/aastd_001.PNG" width="420" height="360" />


* Follow [Client libraries for connecting to Azure Analysis Services](https://docs.microsoft.com/en-us/azure/analysis-services/analysis-services-data-providers) document to install MSOLAP(amd64), MSOLAP(x86), AMO, ADOMD libraries and verify the product version match with that stated in this document.
<img src="https://github.com/subhransusahoo/Azure-Analysis-Services-Workshop/blob/master/images/aastd_002.PNG"/>




* Start Tableau Desktop (64-bit 2018.3 or 32-bit 10.4). Under "Connect", under "To a Server", click "More...", and then click on "Microsoft Analysis Services". In the connection dialog, in Server, copy/paste the Azure Analysis Services server name. Then select "Use a specific username and password". Username is the email address you use to sign in to Azure portal. For password, just give a single space. (yes, just a single space). A pop up window will appear to authenticate you through Azure MFA.
<img src="https://github.com/subhransusahoo/Azure-Analysis-Services-Workshop/blob/master/images/aastd_003.PNG" width="600" height="300"/>

* Done. Sign in through Azure pop-up MFA and you are connected.
