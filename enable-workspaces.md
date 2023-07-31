# Enable Workspaces

## What are Workspaces?

Workspaces are dedicated spaces for developers to manage their Fiserv product integrations and projects. Each workspace may contain a different suite of self-service tools, outlined steps for integration, requirements and sharing permissions as set forth by the specific Fiserv product being integrated to. Developers can create a workspace for any supported Fiserv Product (not all products support workspaces or self-service functionality)

Although each workspace may have different requirements and tools, all workspaces will contain the same set of standard features with a consistent interface as outlined in this how-to guide.

## Enable Workspaces for users

### Create Account on Developer Studio

Please refer our [Create Account Guide](enable-workspaces.md#create-account-on-developer-studio) on this.

### Create Workspace

1. **Create account** or **Log-in**&#x20;

<figure><img src="images/workspace_how_to_create_1 (1).png" alt=""><figcaption><p>Login</p></figcaption></figure>

2. Select **Workspaces** from global header (next to account avatar)

<figure><img src="images/workspace_how_to_1.png" alt=""><figcaption><p>Header</p></figcaption></figure>

3. Create a new workspace&#x20;

&#x20;      a. Enter Name

&#x20;      b. Enter Description

&#x20;      c. Select Product Area from dropdown (preselected at this time)

&#x20;      d. Select Product Integration from dropdown.&#x20;

_<mark style="color:red;">Please note: If you do not find your product in the dropdown, please shoot us a message using our</mark>_ [Support](https://github.com/fiserv/support/issues).

&#x20;     e. Hit the **Create Workspace** button

<figure><img src="images/workspace_how_to_create_3.png" alt=""><figcaption><p>Create</p></figcaption></figure>

### Manage Workspace

1. **Create account** or **Log in**

<figure><img src="images/workspace_how_to_create_1.png" alt=""><figcaption><p>Login</p></figcaption></figure>

2. Select **Workspaces** from global header (next to account avatar)

<figure><img src="images/workspace_how_to_1 (1).png" alt=""><figcaption></figcaption></figure>

3. Select specific workspace from the left navigation or workspace cards

<figure><img src="images/workspace_how_to_manage_3 (1).png" alt=""><figcaption><p>Left Nav</p></figcaption></figure>

4. View workspace Summary

<figure><img src="images/workspace_how_to_manage_4.png" alt=""><figcaption><p>Summary</p></figcaption></figure>

5. Manage Credentials

&#x20;   a. Click **Credentials** on the tab to go to the Credentials page

<figure><img src="images/workspace_how_to_manage_13 (1).png" alt=""><figcaption><p>Credentials</p></figcaption></figure>

&#x20;   b. View MID (Merchant Identifier) details by selecting the **View** button in MID table

<figure><img src="images/workspace_how_to_manage_6.png" alt=""><figcaption><p>MID</p></figcaption></figure>

&#x20;  c. Add/Create API Key by selecting the **Create API key** button

<figure><img src="images/workspace_how_to_manage_7.png" alt=""><figcaption><p>API key</p></figcaption></figure>

     i. Select MID from dropdown. This will be the MID associated with the API key you are creating. _This step might differ for different tenants._

     ii. Name the API Key you are creating

     iii. Select Environment (if available)

     iv. Add Features (if applicable)

     v. Hit the **Create** button

     vi. Download API Key details as a pdf file (this is your one chance to save the API Key details including secret)

d. Add/Create CSR (Certificate Signing Requests) by selecting the **Create CSR** button             i. Enter the common name (name your CSR)

&#x20;            ii. Select Apple Pay from wallet dropdown

&#x20;            iii. Enter Organization Name

&#x20;            iv. Enter Organization Unit

&#x20;            v. Select Country/Region from dropdown

&#x20;            vi. Enter State/Province

&#x20;            vii. Enter City/Locality

&#x20;            viii. Enter an optional description

&#x20;            ix. Hit **Create** button

<figure><img src="images/workspace_how_to_manage_10.png" alt=""><figcaption><p>Add CSR</p></figcaption></figure>

e. View CSR Details by selecting the **View** button in the CSR table (only available after creating/adding a CSR)

<figure><img src="images/workspace_how_to_manage_11.png" alt=""><figcaption><p>CSR Detail</p></figcaption></figure>

f. Download CSR and upload to Apple to complete the CSR process for your application

<figure><img src="images/workspace_how_to_manage_12.png" alt=""><figcaption><p>Download CSR</p></figcaption></figure>

6. Update Settings

a. Click **Settings** on the tab to go to the Settings page

<figure><img src="images/workspace_how_to_manage_13.png" alt=""><figcaption><p>Click Settings</p></figcaption></figure>

b. Hit **Edit** button

   i. Change Workspace Name

   ii. Change Workspace Description

<figure><img src="images/workspace_how_to_manage_14.png" alt=""><figcaption><p>Edit Settings</p></figcaption></figure>

c. Delete Workspace by hitting the **Delete** button

<figure><img src="images/workspace_how_to_manage_15 (1).png" alt=""><figcaption><p>Delete WS</p></figcaption></figure>

7. Gated Content

You can also use workspaces for 'Gated Content'. "Gated Content" is a mechanism developed to control file visibility and permissions on Developer Studio. Read more about this here: [Gated Content](how-to-use-gated-content.md)

