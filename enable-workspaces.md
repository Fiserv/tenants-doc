# What are Workspaces?

Workspaces are dedicated spaces for developers to manage their Fiserv product integrations and projects. Each workspace may contain a different suite of self-service tools, outlined steps for integration, requirements and sharing permissions as set forth by the specific Fiserv product being integrated to. Developers can create a workspace for any supported Fiserv Product (not all products support workspaces or self-service functionality)

Although each workspace may have different requirements and tools, all workspaces will contain the same set of standard features with a consistent interface as outlined in this how-to guide.


# Enable Workspaces for users

## Create Account on Developer Studio
Please refer our [Create Account Guide](?path=/create-account-on-developer-studio.md/) on this.


## Create Workspace
1. **Create account** or **Log-in**

![Login](./images/workspace_how_to_create_1.png "Login")

2. Select **Workspaces** from global header (next to account avatar)

![Header](./images/workspace_how_to_create_2.png "Header")

3. Create a new workspace

  a. Enter Name

  b. Enter Description

  c. Select Product Area from dropdown (preselected at this time)

  d. Select Product Integration from dropdown.
   Please note: If you do not find your product in the dropdown, please shoot us a message using our [Support (https://github.com/fiserv/support/issues).

  e. Hit the **Create Workspace** button

![Create](./images/workspace_how_to_create_3.png "Create")


## Manage Workspace
1. **Create account** or **Log in**

![Login](./images/workspace_how_to_manage_1.png "Login")

2. Select **Workspaces** from global header (next to account avatar)

![Header](./images/workspace_how_to_manage_2.png "Header")

3. Select specific workspace from the left navigation or workspace cards

![Left Nav](./images/workspace_how_to_manage_3.png "Left Nav")

4. View workspace Summary

![Summary](./images/workspace_how_to_manage_4.png "Summary")

5. Manage Credentials

  a. Click **Credentials** on the tab to go to the Credentials page
  
![Credentials](./images/workspace_how_to_manage_5.png "Credentials")
  
  b. View MID (Merchant Identifier) details by selecting the **View** button in MID table
  
![MID](./images/workspace_how_to_manage_6.png "MID")
  
  c. Add/Create API Key by selecting the **Create API key** button
  
![API key](./images/workspace_how_to_manage_7.png "API key")
  
&emsp;&emsp;&emsp;&emsp; i. Select MID from dropdown. This will be the MID associated with the API key you are creating.

&emsp;&emsp;&emsp;&emsp; ii. Name the API Key you are creating

&emsp;&emsp;&emsp;&emsp; iii. Select Environment (if available)

&emsp;&emsp;&emsp;&emsp; iv. Add Features (if applicable)

&emsp;&emsp;&emsp;&emsp; v. Hit the **Create** button
    
&emsp;&emsp;&emsp;&emsp; vi. Download API Key details as a pdf file (this is your one chance to save the API Key details including secret)

![Create API key](./images/workspace_how_to_manage_8.png "Create API key")
  
  d. Add/Create CSR (Certificate Signing Requests) by selecting the **Create CSR** button
  
![Select CSR](./images/workspace_how_to_manage_9.png "Select CSR")
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; i. Enter the common name (name your CSR)
    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ii. Select Apple Pay from wallet dropdown

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; iii. Enter Organization Name

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; iv. Enter Organization Unit

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; v. Select Country/Region from dropdown

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; vi. Enter State/Province

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; vii. Enter City/Locality

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; viii. Enter an optional description

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ix. Hit **Create** button

![Add CSR](./images/workspace_how_to_manage_10.png "Add CSR")
  
  e. View CSR Details by selecting the **View** button in the CSR table (only available after creating/adding a CSR)
  
![CSR Detail](./images/workspace_how_to_manage_11.png "CSR Detail")
  
  f. Download CSR and upload to Apple to complete the CSR process for your application
    
![Download CSR](./images/workspace_how_to_manage_12.png "Download CSR")

6. Update Settings

  a. Click **Settings** on the tab to go to the Settings page
    
![Click Settings](./images/workspace_how_to_manage_13.png "Click Settings")
  
  b. Hit **Edit** button
  
&emsp;&emsp; i. Change Workspace Name

&emsp;&emsp; ii. Change Workspace Description
  
![Edit Settings](./images/workspace_how_to_manage_14.png "Edit Settings")
  
  c. Delete Workspace by hitting the **Delete** button
    
![Delete WS](./images/workspace_how_to_manage_15.png "Delete WS")



