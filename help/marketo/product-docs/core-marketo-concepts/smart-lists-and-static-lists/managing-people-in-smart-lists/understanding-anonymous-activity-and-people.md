---
unique-page-id: 1147322
description: Understanding Anonymous Activity and People - Marketo Docs - Product Documentation
title: Understanding Anonymous Activity and People
---

# Understanding Anonymous Activity and People {#understanding-anonymous-activity-and-people}

The first time someone visits a Marketo [l `anding page`](http://docs.marketo.com/display/DOCS/Personalizing+Landing+Pages)  (or a page on your website that has the [Munchkin Tracking Code](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), Marketo creates an *anonymous **activity* and uses a browser cookie to track it. Once it's identified, it becomes a person and the history associated with their browser cookie is merged in.

**An Anonymous** activity is created when someone:

* Visits your Marketo landing page the first time.

* Visits a page on your site that has [Munchkin tracking](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).

* Clicks the [View as Web Page](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) link in a Marketo email.

>[!NOTE]
>
>Unlike other links in Marketo emails,  [View as Web Page](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) is not tracked as an email click.

An anonymous activity is merged into a new or existing person when someone:

* Clicks a [link in a Marketo email](../../../../product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).
* Fills out a Marketo [Form](../../../../product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md).
* Uses Marketo's [SOAP](http://docs.marketo.com/pages/viewpage.action?pageid=7509846) or [Munchkin](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) API (for developers) to associate an anonymous person with a known record.

One name in the database might be tied to many cookies because people often use different devices and browsers to visit your site.

>[!NOTE]
>
>When anonymous records are merged into a new or existing person record, custom field values will **not** transfer over.

