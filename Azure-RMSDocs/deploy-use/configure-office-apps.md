---
# required metadata

title: Configuration for clients to use Office apps with Azure RMS from AIP
description: Information and instructions for admins to configure Office apps to work with the Azure Rights Management service from Azure Information Protection.
author: cabailey
ms.author: cabailey
manager: mbaldwin
ms.date: 02/08/2017
ms.topic: article
ms.prod:
ms.service: information-protection
ms.technology: techgroup-identity
ms.assetid: ec269afe-4e87-4cc1-9144-5fbb594b412e

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: esaggese
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Office apps: Configuration for clients to use the Azure Rights Management service

>*Applies to: Azure Information Protection, Office 365*


Use this information to determine what you need to do so that Office apps work with the Azure Rights Management service from Azure Information Protection.

## Office 2016 and Office 2013
Because these later versions of Office natively support the Azure Rights Management service, no client computer configuration is required to support the information rights management (IRM) features for applications such as Word, Excel, PowerPoint, Outlook, and Outlook on the web. All users have to do, is sign in to their Office applications with their [!INCLUDE[o365_1](../includes/o365_1_md.md)] credentials. They can then can protect files and emails, and use files and emails that have been protected by others.

However, we recommend that you supplement these applications with the Azure Information Protection client, so that users get the benefit of the Office add-in and support for additional file types. For more information, see [Azure Information Protection client: Installation and configuration for clients](configure-client.md).

## Office 2010
For client computers to use the Azure Rights Management service with Office 2010, they must have the Azure Information Protection client or the Rights Management sharing application for Windows. No further configuration is required other than users must sign in with their [!INCLUDE[o365_1](../includes/o365_1_md.md)] credentials and they can then protect files and use files that have been protected by others.

For more information about the Azure Information Protection client, see [Azure Information Protection client: Installation and configuration for clients](configure-client.md).

[!INCLUDE[Commenting house rules](../includes/houserules.md)]
