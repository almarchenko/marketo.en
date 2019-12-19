---
Title: Create-a-Custom-Field-in-Marketo
Description: 
---

# Create a Custom Field in Marketo

If you need a new custom field in Marketo to store/capture data, here's how to create one.

<br>&nbsp;

1. Go to Admin and click Field Management.

   ![Image One](assets/create-a-custom-field-in-marketo/1.png "Image one! Yay!")

   >[!TIP]
   >
   >If you want the fields to be kept in sync with your CRM, create them in the CRM and they will automatically be created in Marketo.

1. Click New Custom Field.

   ![Image Two](assets/create-a-custom-field-in-marketo/2.png "Image Two! Yussss!")

1. Choose the field Type. This will change how it is rendered in smart lists and forms in Marketo.

   ![Image Three](assets/create-a-custom-field-in-marketo/3.png "Image three!")

   >[!TIP]
   >
   >Check out the [Custom Field Types Glossary](https://docs.marketo.com/display/DOCS/Custom+Field+Type+Glossary).

1. Enter the Name as you want it to appear in Marketo. The API Name is automatically generated. You can tweak it, but it cannot be renamed once set. Click Create when done.

   ![Image Four](assets/create-a-custom-field-in-marketo/4.png "Image four! You are done now")

>[!CAUTION]
>
>Field names cannot start with the following characters: .  &  +  [  ].

>[!NOTE]
>
>The API name is used by the SOAP API and other backend processes.

You can now use this custom field in forms, flow steps and smart lists!