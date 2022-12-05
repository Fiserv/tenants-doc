# What is Gated Content?

"Gated Content" is a mechanism developed to control file visibility and permissions on Developer Studio. 

The different levels of accesses are:

**Public Access** : when all users can access the files publicly. 

**Private Access** : when a user can only view the files when they are signed in Developer Studio. 

**Private Entitled Access** : when signed in users with the appropriate access or entitlements to the files can access them. This is the most protected level of access. To gain this access users have to become a member of the entitled group.


# Enable Gated Content access for Markdown files

The document-explorer-definition.yaml in the config folder defines documentation tree on left navigation panel and this is where the file accesses needs to be added. If a file has "access: public" defined for it, then everyone can see it. 

![public_access](./images/GC_public_access.png)


If the file has "access: private" and "groups: [no groups specified]" meaning, only users who have signed in Developer Studio are permitted to view it. If the file has "access: private" and "groups: [ABC_BANK]" meaning, only users who have signed in Developer Studio and also belong to the group "ABC_BANK" are permitted to view it. Multiple groups can also be defined here like  "groups: [ABC_BANK, XYZ_BANK]"

![private_access](./images/GC_private_access.png)

Also the users can view and download these entitled files when they create a workspace for the product.

![private_entitled_access](./images/GC_private_entitled_access.png)


> Please Note: Workspace needs to be enabled for a product. So in case its not enabled please open a GitHub ticket with Developer Studio with label as "enhancement"

# Enable Gated Content access for API endpoints

___Coming soon...___


# Enable Gated Content access for other Assets

___Coming soon...___


# Provide 'Private Entitled Access' to users

> As of today this part is manual and solely maintained by Developer Studio Team. As part of the future road map, Dev Studio team would be developing a page for administrators from which they could grant access. 

## Tenant's Responsibilities

1. Tenants have to provide a list of the user access groups like "TRANSARMOR_P2PE_PIMS", etc. The naming convention is in all caps and separated by '_'. 

2. Tenants would have to share the list of user email addresses who register at Developer Studio because the user mapping part is currently manual. The backend mapping process ('user' to 'user access groups') would then be handled by the Dev Studio team. 


# Admin UI and Notification Service for users

___Coming soon...___


