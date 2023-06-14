# rootstockAmortizationEnhancements
Enhancements to Rootstock Amortization Module
==================================================
 
This solution includes the following enhancements to Rootstock's Amortization Module:
1. Enforce sequential run of Amortization Processing - prevent a user from 'skipping' a month when executing a later month than the one that should be run next
2. A new custom object called 'Amortization Schedule by Month', which is automatically generated using a flow, and which can be used to report on future/past amortizations by month.
3. A custom report type and a report titled 'Amortization Schedules with Monthly Details'

After deploying this solution, please take the following steps:
1. Activate the two flow:
   - Amortization Schedule: Create Monthly Schedules
   - SO Amortization: Ensure that processing periods are not skipped
2. Assign the permission set 'Amortization Monthly Schedules' to any user that needs to be able to see the monthly schedules.
3. Add the 'Amortization Schedule by Month' related list to the Amortization Schedule Page Layout

 
<a href="https://githubsfdeploy.herokuapp.com?owner=getPraxis&amp;repo=rootstockAmortizationEnhancements">
  <img src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png" alt="Deploy to Salesforce" />
</a>

How to Install the Amortization Enhancements
[![How to install Amortization Enhacements](../media/Enhancements%20to%20Rootstock%20Amortization.png?raw=true "image_tooltip")](https://screencast.getpraxis.com/recordings/bvaOG1XNSMDLov0sqoUo)
