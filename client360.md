# Client 360 Guide

Client 360 is Fiserv's official tool for managing client inquiries and providing a centralized platform for tracking, resolving, and analyzing customer interactions. This guide outlines the purpose of Client 360, steps for integration, and how clients can use it effectively.

---

## Steps for Integration

To integrate Client 360 into your workflow, follow these steps:

### Step 1: Request Assignment Group

Request an assignment group using [ServiceNow Service Catalog request](https://fiservservicepoint.fiservapps.com/now/nav/ui/classic/params/target/com.glideapp.servicecatalog_cat_item_view.do%3Fv%3D1%26sysparm_id%3Df3f33b08db6912003332553fdf96190a)

You will need to refer to the Knowledge Article [KB0180115](https://fiservservicepoint.fiservapps.com/kb?id=kb_article_view&sysparm_article=KB0180115&sys_kb_id=3452d7c01b41a0104921997f034bcb78) for the support group information template that you need to fill out and attach to the request.

- For any issues you can reach out to matthew.parmigiani@Fiserv.com who may be able to assist you.

### Step 2: Request User Access

Your main resource will be [KB0167871](https://fiservservicepoint.fiservapps.com/kb?id=kb_article_view&sysparm_article=KB0167871&sys_kb_id=b62202491bbb805c79da53d07e4bcb35) which outlines the various clienty 360 members and roles along with how to configure/set them.

For the simplest approach to getting access to the Client 360 portal and viewing inquiries, here are the steps.

1. For access to Client360, users need to be added to Assignment groups, For example: TOP.1.Developer Studio- CustomerSupport in ServiceNow via the same request as Step 1. In this case, you'll need to select `Modify an existing group` then `Add user(s) to Group`.

    Once they are added to group in ServiceNow. It takes 24-48 hours for the account to sync with Client360. 
2. Next, users will need access to Client 360. This should be done part of the previous step but if this syncing process fails, ask the point of contact of first ticket to `Add Members to IP` for you to get access to Client360.
    - An email titled 'Add Members to IP' will have attachments to guide you to login to Inquiry Point/Client 360 using FUEL ID upon being added.


Note: For Client 360 accounts that have gone into inactive state: According to the audit process, we require an inquiry to add your account or reenable your access. A colleague or your manager can create this inquiry on your behalf. For details on how to initiate the request, please refer to https://enterprise-confluence.onefiserv.net/x/R7-CE.

Account expiration: Acounts will be locked after a certain timeframe if inactive/not logged in.

- 7 days for new user
- 30 days for existing user

For Client360/Inquiry Point support questions you can reach out to Galina.Hennen@Fiserv.com

---

## How Clients Use Client 360

Clients interact with Client 360 in the following ways:

### Submit Inquiries

Customers on Developer Studio can create an account to `Create an issue` using the blue Help bubble in the bottom right of the page. Generally, they will select a product along with their inquiry which will help reassign the inquiry to your assignment group if the request makes sense.

#### Inquiry Types

You can provide us any number of assignment group(s) for various inquiry types. Here are the categories we most commonly see. You can have one or more type be assigned to a single assignment group.

- Technical question: This relates to issues with implementing sandbox/mock API calls and questions about documentation on how to integrate, versioning, or release notes/upcoming changes.
- Sales: Prospective customer would like to get onboarded. This is asked on the `promotion form` when you request to become a production tenant. If you provide neither a Client 360 assignment nor an email, we will default to sending the customer to getsolutions@fiserv.com
- Production issue: This is for select few products such as Commerce Hub, Banking Hub, and other products which has gone through partner planning to have a dedicated workspace which host customer API keys. This could also apply to if a customer mentions that their API endpoint or credentials has stopped working. In general, we will refer them back to the official Fiserv Client 360 portal at https://client360.fiservapps.com/Client360/login but if you provide us with an assignment group we can use that as well.

### Track Inquiry Activity

Clients will receive an email if the inquiry is responded to. Please inform them to reply to the email if they want to add further comments or questions. They cannot get access to the inquiry point itself to view the ticket at the current time.

It is advised that once you reply to an inquiry, you should allow 3 days for them to add follow-up questions or comments before resolving the ticket.

---

## Best Practices for Using Client 360

- **Assign Clear Ownership**: Ensure each inquiry is assigned to the appropriate assignment group or individual for resolution. If you believe that we have misassigned a ticket to you team, please feel free to reassign it back to `TOP.1.Developer Studio- CustomerSupport`.
- **Maintain Accurate Records**: Make sure to update the `Pending code` if awaiting client response and resolve tickets in a timely manner.
- **Provide Timely Updates**: Respond to client inquiries promptly to maintain trust and satisfaction, our assignment group usually sends us an email when a ticket has been assigned to us.
