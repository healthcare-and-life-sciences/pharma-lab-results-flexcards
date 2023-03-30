![](/images/ahlsbanner.png)

# A-HLS Pharma Lab Results FlexCards Documentation

## Overview

This FlexCard enables the user to see lab results at a glance. In addition, the user can order a retest or set the resolution directly from this interface.

![](/images/pharma-lab-results-screenshot.png)

---

## Business Objective

This Omnistudio asset provides the ability to expose lab data, which is often stored outside of Salesforce in a LIMS system or medical record repository, into a Case record page so that information can be shared with a patient or provider without the agent having to pivot to another application. In addition, it allows the agent to view multiple levels of information (such as Accession, Result, and Test-related details) in a single view.

## Business Value and Benefits

-    Contributes to the Patient 360 view in the Case Object which increases Agent efficiency
-    Increases patient and provider satisfaction by decreasing Case time to resolution

---

## Industry Focus and Workflow

### Primary Industry:

-    Provider
-    Pharma

### Primary User Persona:

-    Contact Center Agent

---

## Package Includes:

### **FlexCards (2)**

-    AccessionsNewCore
     -    Test_Results_Child3 (child FlexCard)

### **OmniScripts (2)**

-    Omni Processes Multipack
     -    Display Test Info - Agent/DisplayTestInfo/Display Test Info
     -    Request a Retest - Agent/RequestARetest/Request a Retest

---

## Configuration Requirements

### Pre-Install Configuration Steps:

1. For this FlexCard, you will need a data source for test results and test information which are not included in this data pack. This source can be from a third-party or a custom object in Salesforce. For demo purposes, this data pack includes static test data in the FlexCards and Omniscripts.
2. Once you have a source, you will need to configure Integration Procedures and/or Data Raptors accordingly and add those to the FlexCards and Omniscripts and remove the static data.

#### Install the Data Pack

1. Follow the download steps presented on the Accelerate HLS website for this Accelerator.

     1. Alternatively, you may download the Data Pack folder in the following GitHub repository: **https://github.com/healthcare-and-life-sciences/pharma-lab-results-flexcards**

1. Then, complete the following steps to import them into your Salesforce org.

     1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
     2. Click on '**Installed**' and on the right side click on '**Import from**'.
     3. Select '**From File**' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '**Install**'.
     4. When prompted to Activate the OmniScript, choose **Not Now**.

### Post-Install Configuration Steps:

1. Click on **App Launcher** → Search for “FlexCards”

     1. Navigate to the recently installed FlexCard in the list view
     2. Open the FlexCard
     3. Click **Activate** and select the appropriate Publish Options
     4. For more information regarding activating FlexCards, please see this article: https://help.salesforce.com/s/articleView?id=sf.os_activateconfigureand_publish_flexcards_24744.htm&type=5

1. Add the installed FlexCard to the lightning page layout of your choosing.

1. Refer to the following articles for more information regarding adding FlexCards to a Lightning or Experience page:

     1. https://help.salesforce.com/s/articleView?id=sf.os_add_a_flexcard_to_a_lightning_page.htm&type=5
     2. https://help.salesforce.com/s/articleView?id=sf.os_add_a_flexcard_to_an_experience_page.htm&type=5

---

## Assumptions

1. A customer has licenses for Health Cloud, and either the HINS Managed Package installed, or with OmniStudio activated in Health Cloud. These solutions have been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package or OmniStudio with Health Cloud are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved.
5. This tool is intended to provide capabilities for Customers to configure, customize, and optimize use of their implemented Salesforce Services, including potential integration with external data sources. Customers: (i) are solely responsible for their implementation and use of this tool; (ii) accept the tool as-is and without any warranties, in accordance with the governing Salesforce Developer Program Terms; and (iii) must ensure that their use of this tool meets their own use case needs and compliance requirements (including any applicable healthcare or privacy laws, rules, and regulations)

---

## Revision History

-    **Revision Short Description (Month Day, Year)**

     -    Initial (January 12, 2023)
     -    Update FlexCards and Omniscripts to use Core OmniStudio (March 30, 2023)
