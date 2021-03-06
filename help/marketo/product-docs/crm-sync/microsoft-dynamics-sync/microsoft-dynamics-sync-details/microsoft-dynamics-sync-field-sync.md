---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -Field Sync
---

# Microsoft Dynamics Sync: Field Sync {#microsoft-dynamics-sync-field-sync}

Marketo to Dynamics sync is super powerful. Here are the details.

## How are field details kept in sync between the two systems? {#how-are-field-details-kept-in-sync-between-the-two-systems}

The sync is bidirectional for lead and contact entities. If you make changes to a lead or contact in Dynamics or a person in Marketo, your updates will be reflected in both systems.

For account, user, opportunity, team, and custom entities, the sync is one-way: Dynamics to Marketo. If you make changes to these entities in Dynamics, your updates will be reflected in Marketo.

## What if changes are made to the same field in both systems at the same time? (Data Collision) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Although this is rare, Marketo will win for people (leads) and Dynamics will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department. For one-way sync entities, Dynamics will always win.

## Can I create a field in Dynamics using Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

No, this is not currently supported.

## I created a field in Dynamics. Can I sync it to Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Yes, you can [sync the field](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) as long as your sync user has access to it in Dynamics.

What fields will sync to Marketo?

You can [select fields to sync](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) during setup.

## What if I need to add a custom field after Marketo and Dynamics are synced? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

You can add fields at any time and expect the data to be refreshed from Dynamics to Marketo. See [Use Quick Sync with Microsoft Dynamics for a New Custom Field](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) for details.

>[!MORELIKETHIS]
>
>* [Use Quick Sync with Microsoft Dynamics for a New Custom Field](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md)
>

