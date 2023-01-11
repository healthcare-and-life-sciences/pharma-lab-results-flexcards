![](/images/ahlsbanner.png)

# A-HLS Pharma Lab Results FlexCards Documentation

## Overview

This FlexCard enables the user to see lab results at a glance. In addition, the user can order a retest or set the resolution directly from this interface.

![](/images/pharma-lab-results-screenshot.png)

---

## Business Objective

Add Accelerator Objective

## Business Value and Benefits

-    Add
-    Add

-    Add
-    Add

---

## Industry Focus and Workflow

### Primary Industry:

-    Healthcare

### Primary User Persona:

-    Healthcare Professional

---

## Package Includes:

### **FlexCard (1)**

-    AccessionsNew
     -    Test_Results_Child3 (child FlexCard)

### **OmniScript (2)**

-    Display Test Info - Agent/DisplayTestInfo/Display Test Info
-    Request a Retest - Agent/Request_a_Retest/Request a Retest

---

## Configuration Requirements

### Pre-Install Configuration Steps:

1. For this FlexCard, you will need a data source for test results and test information which are not included in this data pack. This source can be from a third-party or a custom object in Salesforce.
2. Once you have a source, you will need to configure Integration Procedures and/or Data Raptors accordingly and add those to the Omniscripts in place of the "Set Values" step.

#### Install the Data Pack

1. Follow the download steps presented on the Accelerate HLS website for this Accelerator.

2.   1. Alternatively, you may download the Data Pack folder in the following GitHub repository: **https://github.com/healthcare-and-life-sciences/pharma-lab-results-flexcards**

3. Then, complete the following steps to import them into your Salesforce org.

4.   1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
     2. Click on '**Installed**' and on the right side click on '**Import from**'.
     3. Select '**From File**' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '**Install**'.
     4. When prompted to Activate the OmniScript, choose **Not Now**.

### Post-Install Configuration Steps:

1. Click on **App Launcher** → Search for “FlexCards”

2.   1. Navigate to the recently installed FlexCard in the list view
     2. Open the FlexCard
     3. Click **Activate** and select the appropriate Publish Options
     4. For more information regarding activating FlexCards, please see this article: https://help.salesforce.com/s/articleView?id=sf.os_activateconfigureand_publish_flexcards_24744.htm&type=5

3. Add the installed FlexCard to the lightning page layout of your choosing.

4.   1. Refer to the following articles for more information regarding adding FlexCards to a Lightning or Experience page:

     2.   1. https://docs.vlocity.com/en/Add-a-FlexCard-to-a-Lightning-Page.html
          2. https://docs.vlocity.com/en/Add-a-FlexCard-to-an-Experience-Page.html

---

## Assumptions

1. A customer has licenses for Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved.

---

## Revision History

-    **Revision Short Description (Month Day, Year)**

-    -    Initial
     -    Add

-
