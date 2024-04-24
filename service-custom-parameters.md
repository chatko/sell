---

copyright:

  years: 2022, 2024

lastupdated: "2024-04-24"

keywords: IBM Cloud, selling services, custom, parameters

subcollection: sell

---

{{site.data.keyword.attribute-definition-list}}


# Adding custom service parameters for your service
{: #service-add-custom-parameters}

When you onboard your service to {{site.data.keyword.Bluemix}}, you might need additional information from your customers. To get the additional information, you can add custom input fields for your product in {{site.data.keyword.cloud_notm}} Partner Center. Customers can use the custom fields to input any additional information that you need when they create instances of your product.
{: shortdesc}

## Adding custom input fields
{: #service-add-field}

Partner center offers two input options for the required customer information. You can choose a **Simple** input option to add custom fields like short text and paragraph entries. Or, for advanced use cases that require more complex inputs, you can choose the **Advanced** option to receive the input as JSON code.

### Simple input option to add custom fields
{: #service-simple}

To add custom fields for simple use cases, complete the following steps:

1. In the {{site.data.keyword.cloud_notm}} console, click the **Navigation Menu** icon ![Navigation Menu icon](../icons/icon_hamburger.svg "Menu") > **Partner Center** > **My products**.
1. Select your product.
1. Click **Catalog entry**.
1. To add custom setup options, click **Add custom fields**.
1. Select **Simple**.
1. Select *Short text entry*, *Paragraph entry*, or *Option selection* based on how you want to receive the input from customers.
1. Complete each field.

   You can test and review how the custom fields are displayed to customers by looking at the preview section of the side panel. This preview is not saved. 
   {: tip}

1. Click **Done**. You can edit your custom fields by clicking the **Edit** icon ![Edit icon](../icons/edit-tagging.svg "Edit"). To delete your custom fields, click the **Delete** icon ![Delete icon](../../icons/delete.svg "Delete").

### Advanced input option to add custom fields
{: #service-advanced}

To add custom fields for complex use cases, complete the following steps:

1. In the {{site.data.keyword.cloud_notm}} console, click the **Navigation Menu** icon ![Navigation Menu icon](../icons/icon_hamburger.svg "Menu") > **Partner Center** > **My products**.
1. Select your product.
1. Click **Catalog entry**.
1. To add custom setup options, click **Add custom option**.
1. Select **Advanced**.
1. Create custom input fields by using the JSON editor.
1. Click **Done**. You can edit your JSON entry from the **Catalog entry** page by clicking **Edit JSON**.

For more information about service parameters, see [Service parameter definitions and examples](/docs/sell?topic=sell-service_parameters_def_examples).
