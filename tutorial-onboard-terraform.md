---

copyright:
  years: 2021, 2024

lastupdated: "2024-02-02"


keywords: onboard software, third-party software, sell on IBM Cloud, partner center, validate, test, Terraform, terraform template

subcollection: sell

content-type: tutorial
services: Terraform
account-plan: paid
completion-time: 45m

---

{{site.data.keyword.attribute-definition-list}}


# Onboarding your Terraform template
{: #terraform-template-onboard}
{: toc-content-type="tutorial"}
{: toc-services="Terraform"}
{: toc-completion-time="45m"}

This tutorial walks you through how to onboard a Terraform template to your private catalog in {{site.data.keyword.cloud}}.
{: shortdesc}

## Before you begin
{: #terraform-template-onboard-prereqs}

1. Create your Terraform template. For more information, see [Creating Terraform templates](/docs/schematics?topic=schematics-create-tf-config).
1. Test your Terraform template by running the following commands from the Terraform CLI:

   * `terraform init`
   * `terraform validate`

1. Upload your Terraform template to a GitHub release and create a `.tgz` file. For more information, see [Upload your Terraform template and readme file to your GitHub repository](https://github.com/IBM-Cloud/isv-vsi-product-deploy-sample/tree/main#upload-your-terraform-template-to-a-github-release){: external}.

   Use the [latest release of the sample Terraform code](https://github.com/IBM-Cloud/isv-vsi-product-deploy-sample/releases/tag/v1.0 ){: external} as an example of how to set up your repository.
   {: tip}

1. Verify that you're assigned the correct roles. For Terraform, you need the following {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) roles.

   * Administrator on all account management services and all IAM services
   * Editor on the catalog management service
   * Manager service access role for IBM Cloud Schematics
   * Operator platform role for VPC Infrastructure
   * Editor on the software instance service
   * The required permission to complete a specific task

## Import your Terraform template
{: #terraform-template-onboard-import}
{: step}

1. In the {{site.data.keyword.cloud_notm}} console, click the **Navigation Menu** icon ![Navigation Menu icon](../icons/icon_hamburger.svg "Menu") > **Partner Center** > **My products**.
1. Select the product that you're onboarding.
1. From the Software tab, click **Import a version**.
1. Choose **Terraform** as your deployment method.
1. Select the type of repository.
1. Enter the **example Terraform** URL as your source URL.
1. Enter the software version in the format of major version, minor version, and revision, for example, `1.0.0`.
1. Click **Add version**.

## Review the version details
{: #terraform-template-review-version}
{: step}

From the Configure version tab, you can review your version details. After you review your version details, click **Next**.

## Configure the deployment values
{: #terraform-template-onboard-cfgdeploy}
{: step}

After you review the version details, you're ready to configure the deployment values.

1. If you need to specify the Terraform runtime version that you want Schematics to use, click the **Override the default Terraform runtime version** checkbox and enter a version.
1. From the Configure the deployment details section, click **Add deployment values**.
1. Select the **Parameter** checkbox to select all options, and click **Add**.
1. To customize which parameters are required for users to specify during the installation and which ones are hidden from users, select a parameter and click **Edit**. Click the checkboxes to configure the values and click **Save**.

## Edit output value descriptions
{: #output-values}
{: step}

{{site.data.content.description-output-values}}

{{site.data.content.note-output-values}}

{{site.data.content.steps-desc-output-values}}

{{site.data.content.steps-output-value}}

{{site.data.content.define-IAM-access}}

## Set the license requirements
{: #terraform-template-onboard-cfg-license}
{: step}

If users are required to accept any license agreements beyond the {{site.data.keyword.cloud_notm}} Services Agreement, provide the URL to each agreement.

1. From the Add license agreements tab, click **Add license**.
2. Enter the name and URL, and click **Add license**.
3. Enter all additional license agreements, and click **Next**.

## Review your readme file
{: #terraform-template-onboard-review-readme}
{: step}

When users install the software, they can view product information by clicking the Readme file link. This information is generated from the readme file that you uploaded to your source repository.

1. From the Edit readme tab, click the **Edit** icon ![Edit icon](../icons/edit-tagging.svg "Edit").
2. Preview how the information in the readme file is displayed to users when they install the Terraform template.
3. If you need to make changes, edit the repository where you uploaded the Terraform template and re-create the `.tgz` file. Then, you can import the updated file to your private catalog again.
4. Click **Save**.
5. Click **Next**.

## Validate the Terraform template
{: #terraform-template-onboard-validate}
{: step}

1. From the Validate product tab, enter the name of your workspace, select a resource group, select a Schematics region, and click **Next**.

   In the **Tags** field, you can enter a name of a specific tag to attach to your template. This tag is put on the {{site.data.keyword.bplong_notm}} workspace. Tags provide a way to organize, track usage costs, and manage access to the resources in your account.
   {: tip}

1. From the Deployment values section, review your parameter values, and click **Next**.
1. In the Validate version section, select **I have read and agree to the following license agreements**.
1. Click **Validate**.

   To monitor the progress of the validation process, click **View logs**.
   {: tip}

{{site.data.content.manage-compliance}}

## Review requirements
{: #terraform-template-review-reqs}

You must complete validation and any other requirements to publish your Terraform template.

## Next steps
{: #terraform-template-onboard-next}

Go to the Partner Center and submit your request to [publish your Terraform template](/docs/sell?topic=sell-terraform-publish) to the {{site.data.keyword.cloud_notm}} catalog.
