---
title: Teams Phone number management during number porting event
author: sfrancis206
ms.author: scottfrancis
manager: pamgreen
ms.reviewer: pavellatif
ms.date: 01/22/2025
ms.topic: article
ms.tgt.pltfrm: cloud
ms.service: msteams
search.appverid: MET150
audience: Admin
appliesto: 
  - Microsoft Teams
ms.localizationpriority: medium
f1.keywords: 
  - CSH
ms.custom: 
  - ms.teamsadmincenter.voice.phonenumbers.porting.numbermanagement
  - Calling Plans
description: Guide for managing Teams phone number assignments during a number port event.
ms.collection: 
  - M365-voice
  - m365initiative-voice
  - highpri
  - Tier1
---

# Managing number assignments during a Teams number porting event

**APPLIES TO:** ![Image of a checkmark for yes](/office/media/icons/success-teams.png)Microsoft Calling Plans ![Image of a checkmark for yes](/office/media/icons/success-teams.png)Operator Connect ![Image of a checkmark for yes](/office/media/icons/success-teams.png)Direct Routing

This article is for...

## Porting from one Teams PSTN solution to another

There may be times when you are keeping your acquired numbers in Teams, but you are porting the number ownership from one PSTN service provider to another. Porting is supported between all of the [Teams PSTN connectivity types](..\pstn-connectivity.md).

Special Teams administrative considerations follow for the various scenarios.

### Porting from Microsoft Calling Plans

If you're porting your numbers from Microsoft to a different service provider, you must submit a port request with the new service provider. You also need to relay to them a porting PIN that you set in the Teams admin center.

- To define your porting PIN with Microsoft, navigate to the Teams admin center. Go to **Voice** > **Phone numbers**, and on the upper-right corner of the page, select **Actions** > **Manage porting PIN**, and then enter a 10-digit PIN.
- When your new carrier contacts us with the porting request, we'll ask them to provide the PIN you defined.
- If you need further assistance setting up a PIN, contact the [Telephone Number Services - Service Desk](../manage-phone-numbers-for-your-organization/contact-tns-service-desk.md)

If you're moving your Teams PSTN access from Microsoft Calling Plan to a different Teams PSTN service provider but you aren't porting your Microsoft numbers, you can release the unused Microsoft Calling Plan numbers back to Microsoft in one of two ways:

- In Teams admin center, navigate to **Voice** > **Phone numbers**, select the number to release then select **Release**. Enter the displayed code to confirm the release of the number and again select **Release**.
- For large quantities of numbers, follow the [Telephone Number Services - Service Desk](../manage-phone-numbers-for-your-organization/contact-tns-service-desk.md) guidance and create a new case, with case type selected as **Release telephone number - remove phone number from my tenant**.

Removing Microsoft Calling Plan licenses doesn't automatically release the numbers back to Microsoft. Even with no entitlement to assign the reserved numbers, the reserved numbers must still be manually released back to Microsoft.

### Managing numbers when porting between Teams PSTN service providers for the same tenant

If you're porting numbers from a Teams PSTN service provider to Microsoft Calling Plan, for the same tenant, consider the following:

- When 

## Related topics

- [What's the status of your port orders?](port-order-status.md)
- [Different kinds of phone numbers used for Calling Plans](../different-kinds-of-phone-numbers-used-for-calling-plans.md)
- [Manage phone numbers for your organization](../manage-phone-numbers-for-your-organization/manage-phone-numbers-for-your-organization.md)
- [Emergency calling terms and conditions](../emergency-calling-terms-and-conditions.md)
- [Emergency Calling disclaimer label](https://download.microsoft.com/download/9/9/0/990e24c1-eb49-4b52-9306-dbd4c864ed91/emergency-calling-label-(en-us)-(v.1.0).zip)
