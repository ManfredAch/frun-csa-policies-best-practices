# Description
This project provides policies for Focused Run - Advanced Configuration Monitoring - Configuration and Security Analytics. Those policies are the basis for validating configuration items of systems which are stored centrally in Focused Run. Policies comprise a set of rules which are ideally derived from a  hardening guide or a system baseline documention. Those policies are used to calculate compliance status of configuration items using application FRUN CSA Validation.

Besides the policies the project provides some powershell scripts which helps you to setup your policies. 
# Requirements
To use those policies you need [Focused Run for SAP Solution Manager](https://support.sap.com/en/alm/focused-solutions/focused-run.html)
# Download and Installation
Details can found as well here: [Focused Run for SAP Solution Manager](https://support.sap.com/en/alm/focused-solutions/focused-run.html)
in tabs: "Get Focused Run" and "Implement Focused Run". 
Usually a Focused Run Architecture and Project Setup Workshop is performed to to install and configure the Focused Run infrastructure in close cooperation with the customer team: technical deployment, landscape discovery as well as network settings will be discussed. Some managed systems will be connected to Focused Run, including activation of some use cases.
# Configuration
After connecting the managed systems to Focused Run you can start to configure FRUN CSA Validation using the provided policies. Those policies could be uploaded in FRUN CSA Policy Management (FRUN Launchpad / Advanced Configuration Management / tile Configuration and Security Analytics then Links / Policy Management). When creating a new one you many use the Policy Id and Policy Descr of the XML policy as input. Use those policies as a template for your own policies reflecting the requirements of your corporate hardening guides and security policies. Demo: [Configuration and Security Analytics ](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_ce0ht4id)
# Limitations
The number of check items is not limited per policy, however, as a rule of thumb you should not add more than approx. 100 check items to a single policy
# Known Issues
None
# How to obtain support
Please report issues in Focused Run Advanced Configuration Monitoring using SAP's product support channels.
For questions regarding the provided policies or scripts please us [issue template](https://github.com/SAP/frun-csa-policies-best-practices/issues).
# To-Do (upcoming changes)
Updates will be provided on a monthly basis to cover the security note checks
# License
Copyright (c) 2019 SAP SE or an SAP affiliate company. All rights reserved.
This file is licensed under the SAP Sample Code License except as noted otherwise in the [LICENSE file](LICENSE).
