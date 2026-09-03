# Azure-Integration
Extending a virtual on-premises Active Directory environment into a hybrid Azure infrastructure.

🟡 Status: In progress...

**Things needed**
- On-premise infrastructure (I will be using the previous project I built: [Virtual Home Lab](https://github.com/amricalde/Virtual-Home-Lab) )
- [Azure account](https://portal.azure.com/#home)

Project Phases
-
**Phase 0** - Familiarize Azure environment <!--create VM and explore--> <br>
**Phase 1** - Microsoft Entra Connect <!--using this tool to sync on-prem and cloud infrastructure, creating the hybrid environment--> <br>
**Phase 2** - Testing/Verify synchronization <!--making changes to accounts, passwords, folders, access, etc.--> <br>
**Phase 3** - Exploring Azure resources (VMs, Storage, RBAC) <!--for later..--> <br>
**Phase 4** - Automation (PowerShell, Azure CLI, automation)<!--for later..--> <br>


<!--


Helpful links:

Elavating access (When you set the toggle to Yes, you are assigned the User Access Administrator role in Azure RBAC at root scope (/). This grants you permission to assign roles in all Azure subscriptions and management groups associated with this Microsoft Entra tenant. This toggle is only available to users who are assigned the Global Administrator role in Microsoft Entra ID.)
https://learn.microsoft.com/en-us/azure/role-based-access-control/elevate-access-global-admin?tabs=azure-portal%2Centra-audit-logs#perform-steps-at-root-scope 

https://docs.azure.cn/en-us/entra/identity/hybrid/connect/how-to-connect-install-prerequisites 

-->
