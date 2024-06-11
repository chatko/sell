---

copyright:
  years: 2021, 2024

lastupdated: "2024-04-22"

keywords: onboard, SaaS, third-party service, sell on IBM Cloud, partner center, product details, catalog entry, support, pricing, catalog, service name, display name, customize, programmatic name

subcollection: sell

content-type: tutorial
account-plan: paid
completion-time: 10m

---

{{site.data.keyword.attribute-definition-list}}


# Define the product details of your service
{: #svc-define}
{: toc-content-type="tutorial"} 
{: toc-completion-time="10m"} 

This tutorial walks you through the steps for defining specific details about your service in {{site.data.keyword.cloud}} Partner Center. By completing this tutorial, you review and sign the {{site.data.keyword.IBM}} Digital Platform Reseller Agreement, customize your catalog entry and product page, and define support experience.  
{: shortdesc}

This tutorial is one of five in a series that demonstrates how to onboard and publish a service to the {{site.data.keyword.cloud_notm}} catalog. It uses a fictitious company that's called *Example Corp*. As you complete the tutorial, adapt each step to fit your needs.

## Before you begin
{: #svc-define-prereqs}

[Register your service](/docs/sell?topic=sell-svc-register).

## Review and submit the {{site.data.keyword.IBM_notm}} Digital Platform Reseller Agreement
{: #svc-dra}
{: step}

If you plan to offer free or paid, usage-based pricing plans, it is required to review and submit the {{site.data.keyword.IBM_notm}} Digital Platform Reseller Agreement. This legal agreement sets the terms and conditions under which providers can onboard and sell products in {{site.data.keyword.cloud_notm}}. Or, you can upload a custom digital provider agreement in `.pdf`, `.doc`, or `.docx` file format.

Custom digital provider agreements must be reviewed and approved by {{site.data.keyword.IBM_notm}}, which increases the time it takes for you to complete the onboarding process. The uploaded files are scanned for viruses, which might take a few minutes to complete. If a virus is detected, it is recommended to run another virus scan on your file, and then try uploading it again.
{: note}

Complete the following steps to review and submit the {{site.data.keyword.IBM_notm}} Digital Platform Reseller Agreement:

1. In the {{site.data.keyword.cloud_notm}} console, click the **Navigation Menu** icon ![Navigation Menu icon](../icons/icon_hamburger.svg "Menu") > **Partner Center** > **My company**.
1. Click **Edit**.
1. Choose **I plan to offer free and usage-based pricing plans** from the Agreements section.
1. Click the **{{site.data.keyword.IBM_notm}} Digital Platform Reseller Agreement** link to review the agreement.
1. Select **I have read and agree to the {{site.data.keyword.IBM_notm}} Digital Platform Reseller Agreement.**, and click **Save**.

## Provide your service name and type
{: #svc-name}
{: step}

You can add a new product or import an existing product from a private catalog. For the purposes of this tutorial, add a product.

1. From the **My products** page, click **Create**.
1. Click **Create a product**, and click **Next > Start now**.
1. Select **Service > Software as a service** as the type of product that you're onboarding, and click **Next**.

    The product type is used for tax assessment purposes. For more information, see [Selling on IBM Cloud](/docs/sell?topic=sell-selling-clouds).
    {: important}

1. Enter the display name of your product, for example `Example SaaS Product`. Make sure that the name you enter meets the following requirements:
  
   * Use 60 characters or less.
   * Don't include "{{site.data.keyword.cloud_notm}}".
   * Don't include the name of your company, former product names, or pricing details.

1. Optionally, enter the programmatic name of your product, and click **Next**.
1. Review your product details and click **Create**.

## Confirm your display name and programmatic name for approval
{: #svc-progname-review}
{: step}

Your programmatic name is different than the display name that you provided in the previous step. It's either automatically generated for you and includes your company name, or it is provided by you in a customized manner during the previous step. If your company offers multiple products in {{site.data.keyword.cloud_notm}}, the value of each service name includes both the company name and product name.

Your programmatic name must be approved to create your pricing plans or registering your service broker. You can review and make updates to your programmatic name before you submit it for approval. 

Your programmatic name can't be updated after you submit it for review.
{: important}

1. From the Dashboard tab, click **Edit**, enter your updates, and click **Save**.
1. Click **Confirm**.

## Create your service ID
{: #svc-service-id}
{: step}

After your programmatic name is reviewed, you can create your service ID. A service ID is used to identify your service when communicating with other {{site.data.keyword.cloud_notm}} services, for example, when submitting metering usage data for your service. For more information, see [Creating and working with service IDs](/docs/account?topic=account-serviceids&interface=ui).

You're also required to create an API key for your service ID. To create your API key, see [Creating an API key for a service ID](/docs/account?topic=account-serviceidapikeys&interface=ui#create_service_key).


## Provide details for your product
{: #svc-catalog}
{: step}

When your service is published in the catalog, it's represented by a catalog entry and a product page. The contents of your catalog entry include your company or product logo, and a short description. The contents of your product page include a list of features, a detailed description, a link to your product's warranted documentation, and a description of your customer support experience. 

1. Click **Catalog entry**, and enter the URL to your company or product logo, for example `http://svgur.com/i/TTP.svg`.
1. Add a company logo.
1. Provide a short description about your service.
1. From the **Category** list, select the option that best fits how users might use your product, for example, **Databases**. Categories are used to organize similar products in the catalog based on common solutions, function, or use.
1. Enter keywords that users might use when they search the catalog for your service.
1. Provide the URL to the end user license agreement (EULA) that users must agree with to use your product. Do not include billing, payment, or tax terms in this agreement.
1. Provide a list of features that highlights your service's attributes and benefits for users.

   Use a descriptive title and 1 - 2 sentences for each feature. You want the information to be visually scannable for users.
   {: tip}

1. Provide a detailed description of your product that explains its value and what users gain by using it. The detailed description is displayed at the beginning of your product page in the catalog. You can expand on the short description that you provide for your catalog entry, but don't repeat it. 
1. Provide links to high-quality images or videos to help illustrate what your product is, its value, and user benefits. The supported media types are images, videos in MP4 or WebM file format, and videos hosted on YouTube or Vimeo.

   Some examples of effective media include an introductory walkthrough of your product, an explanation of what your product is and why users might want to use it, or a comparison of certain features. 
   {: tip}

1. Provide a link to documentation that helps users understand and learn more about how to use your service.

## Define your support experience
{: #svc-support}
{: step}

Provide details that help users understand how to get support if they encounter issues when they use the service. For more information about providing support information, see [Defining your support experience](/docs/sell?topic=sell-sw-support-details). 

To define your product's support experience, use the following steps:

{{site.data.content.steps-support-experience}}

## Next steps 
{: #pricing-next}

You can now [add your broker](/docs/sell?topic=sell-broker-onboard). 
