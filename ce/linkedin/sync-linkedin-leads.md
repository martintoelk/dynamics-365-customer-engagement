---
title: "Sync leads by using Dynamics 365 Connector for LinkedIn Lead Gen Forms | Microsoft Docs"
description: "Learn how to set up and configure Dynamics 365 Connector for LinkedIn Lead Gen Forms to sync leads from sponsored campaigns on LinkedIn to your Dynamics 365 (online) organization."
ms.date: 07/10/2017
ms.service: crm-online
ms.topic: article
applies_to: "Dynamics 365 (online)"
ms.assetid: 13c8a439-30bc-45a4-bf4e-a25781148a4c
author: "m-hartmann"
ms.author: mhart
manager: sakudes
---
# How to sync [!include[LinkedIn](includes/tn-linkedin.md)] leads by using [!include[Dynamics 365 Connector for LinkedIn Lead Gen Forms](includes/pn-linkedin-solution.md)]

[!include[Pre-release disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

[!include[Dynamics 365 Connector for LinkedIn Lead Gen Forms](includes/pn-linkedin-solution.md)] enables seamless synchronization of [!include[LinkedIn](includes/tn-linkedin.md)] leads to [!include[Dynamics 365](includes/pn-dynamics-crm.md)]. [!include[LinkedIn](includes/tn-linkedin.md)] members can drive leads from [Sponsored Content](https://business.linkedin.com/marketing-solutions/native-advertising) campaigns, based on a variety of calls to action. The [!include[LinkedIn Connector](includes/pn-linkedin-solution-shortest.md)] lets campaign managers sync the leads from [LinkedIn's Lead Gen forms](https://business.linkedin.com/marketing-solutions/native-advertising/lead-gen-ads) to a [!include[Dynamics 365 (online)](includes/pn-dyn-365-online.md)] instance for further nurturing. If a lead is already known in [!include[Dynamics 365](includes/pn-dynamics-crm.md)], the data for that lead will be updated by using the information provided from [!include[LinkedIn](includes/tn-linkedin.md)]; otherwise, a new lead record is created in [!include[Dynamics 365](includes/pn-dynamics-crm.md)].

[//]: # (@Michael, I have a mail out to Renee about this. I didn't realize when I wrote that there are two flavors of Dyn365 for Sales--Business edition and Enterprise edition. Maybe those are what this note is referring to?)
[//]: # (@Nona please note it's the Enterprise Sales app module and the Marketing Business edition, not Sales SMB)
[//]: # (The connector is already installed when you purchase Marketing, Business edition.)
> [!NOTE]
> You need a [!include[Dynamics 365 (online)](includes/pn-dyn-365-online.md)] organization with the Sales app to use the [!include[LinkedIn Connector](includes/pn-linkedin-solution-shortest.md)].

## Quick start guide to install and use the connector

1. A [!include[Dynamics 365 (online)](includes/pn-dyn-365-online.md)] system administrator or customizer installs the [Connector for LinkedIn Lead Gen Forms from Microsoft AppSource](https://go.microsoft.com/fwlink/p/?linkid=850928). [!INCLUDE[proc_more_information](includes/proc-more-information.md)] [Install Dynamics 365 Connector for LinkedIn Lead Gen Forms from AppSource] (install-linkedin-connector.md)

2. Optionally, a campaign manager defines the matching strategy between [!include[LinkedIn](includes/tn-linkedin.md)] leads and [!include[Dynamics 365 (online)](includes/pn-dyn-365-online.md)] lead records, and analyzes individual forms and submissions. [!INCLUDE[proc_more_information](includes/proc-more-information.md)] [Configure the matching strategy to update lead records from LinkedIn leads](configure-matching-strategy.md), [Analyze individual LinkedIn Lead Gen forms and submissions](review-leads.md#analyze-individual-includelinkedinincludestn-linkedinmd-lead-gen-forms-and-submissions).

3. A person filling the roles of both a campaign manager on [!include[LinkedIn](includes/tn-linkedin.md)] and a salesperson in [!include[Dynamics 365](includes/pn-dynamics-crm.md)] authorizes [!include[Dynamics 365](includes/pn-dynamics-crm.md)] to receive data from [!include[LinkedIn](includes/tn-linkedin.md)]. [!INCLUDE[proc_more_information](includes/proc-more-information.md)] [Connect Dynamics 365 and LinkedIn](connect-dynamics-365-linkedin.md)

4. Optionally, a sales manager can review the lead performance in a [!include[Dynamics 365 (online)](includes/pn-dyn-365-online.md)] dashboard. [!INCLUDE[proc_more_information](includes/proc-more-information.md)] [Analyze leads and lead performance](review-leads.md)

### See also
[Install Dynamics 365 Connector for LinkedIn Lead Gen Forms from AppSource] (install-linkedin-connector.md)  
[Establish a connection between Dynamics 365 Connector for LinkedIn Lead Gen Forms and LinkedIn](connect-dynamics-365-linkedin.md)  
[Configure a matching strategy to update leads from LinkedIn Lead Gen ads](configure-matching-strategy.md)  
[Analyze leads and lead performance](review-leads.md)  
[Microsoft Online Services Privacy Statement](http://go.microsoft.com/fwlink/p/?LinkId=512132)