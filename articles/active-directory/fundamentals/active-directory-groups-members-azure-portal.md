---
title: How to add or remove group members using the Azure AD portal | Microsoft Docs
description: How to add or remove users and devices from a group using the Azure Active Directory portal.
services: active-directory
author: eross-msft
manager: mtillman

ms.service: active-directory
ms.workload: identity
ms.component: fundamentals
ms.topic: conceptual
ms.date: 08/23/2018
ms.author: lizross
ms.custom: it-pro
ms.reviewer: krbain
---

# How to: Add or remove group members using the Azure AD portal
Using the Azure AD portal, you can continue to add and remove group members.

## To add group members

1. Sign in to the [Azure AD portal](https://portal.azure.com) using a Global administrator account for the directory.

2. Select **Azure Active Directory**, and then select **Groups**.

3. From the **Groups - All groups** blade, search for and select the group you want to add the member to. In this case, use our previously created group, **MDM policy - West**.

    ![Groups-All groups blade, group name highlighted](media/active-directory-groups-members-azure-portal/group-all-groups-screen.png)

4. From the **MDM policy - West Overview** blade, select **Members** from the **Manage** area.

    ![MDM policy - West Overview blade, with Members option highlighted](media/active-directory-groups-members-azure-portal/group-overview-blade.png)

5. Select **Add members**, and then search and select each of the members you want to add to the group, and then choose **Select**.

    You'll get a message that says the members were added successfully.

    ![Add members blade, with searched for member shown](media/active-directory-groups-members-azure-portal/update-members.png)

6. Refresh the screen to see all of the member names added to the group.

## To remove group members

1. From the **Groups - All groups** blade, search for and select the group you want to remove the member from. Again we'll use, **MDM policy - West**.

2. Select **Members** from the **Manage** area, search for and select the name of the member to remove, and then select **Remove**.

    ![Member info blade, with Remove option](media/active-directory-groups-members-azure-portal/remove-members-from-group.png)

## Next steps

- [View your groups and members](active-directory-groups-view-azure-portal.md)

- [Edit your group settings](active-directory-groups-settings-azure-portal.md)

- [Manage access to resources using groups](active-directory-manage-groups.md)

- [Manage dynamic rules for users in a group](../users-groups-roles/groups-create-rule.md)

- [Associate or add an Azure subscription to Azure Active Directory](active-directory-how-subscriptions-associated-directory.md)
