# SSRS_Migrate
Migrate SSRS Objects to New Server

Powershell scripts to Migrate SSRS Objects from a 2008+ Servers to anything newer.

Uses SQL, WMI, SOAP and REST to export the following objects:
* RDL Reports with embedded DataSources/DataSets
* Shared DataSources
* Shared Data Sets
* PowerBi PBIX files
* Mobile Reports
* KPIs
* Shared Schedules
* Subscriptions
* Users
* Folder Tree Structure
* Folder and Report Permissions
* Config Files
* Encryption Key

Companion Import Script will restore these objects in the following order:
* Users
* FolderTree Structure
* RDL Reports with embedded DataSources/DataSets
* Shared Schedules
* Subscriptions
* Folder and Report Permissions

Must be Sysadmin on both SQL servers for this to work
