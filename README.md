# Network function UDM introduction
### Overview
In this article, I will introduce UDM and through introduce its three services that will be used in the general UE registration procedure (Nudm_UECM service, Nudm_SubscriberDataManagement Service, and Nudm_UEAuthentication Service.) to let everyone understand UDM more clearly.

### UDM
Unified Data Management, responsible for managing information related to UE. When other NFs need to use the UE subscription information, they will obtain that from UDM through the sbi of UDM.

### Nudm_UEAuthentication Service
This service is used by ASUF to retrieve authentication related information, and after authentication, confirm the result.
