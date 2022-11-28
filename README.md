# Welcome to the Tenants Documentation!

These markdown files will provide all the info you need to get going to onboard into the Developer Studio.

## Table of Contents
  - [The Studio Community (Metaphor)](#the-studio-community-metaphor)
    - [What can you do as a Tenant](#what-can-you-do-as-a-tenant)
    - [What must you do as a Tenant](#what-must-you-do-as-a-tenant)
    - [What can you NOT do as a Tenant](#what-can-you-not-do-as-a-tenant)
  - [Directory of files](#directory-of-files)
  - [Developer Studio Demos](#developer-studio-demos)
  - [Below are the steps you need to follow:](#below-are-the-steps-you-need-to-follow)
  - [Getting Help](#getting-help)
  
## The Studio Community (Metaphor)

The way we describe the Developer Studio is that it is a apartment complex and each of you are tenants within the complex.  (hint: Still not sure what a tenant is checkout the [glossary](./glossary.md))

While we, the DevStudio team, are the HOA.

### What can you do as a Tenant
Just like how you move into your apartment you can bring along your furniture (your content) and decorate your apartment (within limits dedicated by the HOA (i.e. DevStudio team)).

1. You create/edit/publish your own documentation and APIs at your liesure
2. You can provide your own live sandbox
3. You can provide your own API management system

### What must you do as a Tenant
Because the Developer Studio is meant to unify all our products under a single portal that means there are guidelines you must follow.

1. You must provide [Basic Tenant Information](./tenant-basics.md) such as name, desctiption, solution, product tags, etc.
2. You must have API documentation in [markdown format](https://www.markdownguide.org/basic-syntax/) and for that use our [Markdown syntax](https://developer.fiserv.com/support/docs/?path=docs/md/extended-syntax.md)
3. You must have a [getting started section](./getting-started-template.md)
4. You must be on open api specification 3.0+
5. You must have Release Notes as part of the documentation that follow our [guidelines](./release-notes-guidelines.md)

Hint: When in doubt look at [Commerce Hub](https://developer.fiserv.com/product/CommerceHub) as an example of what to do.

### What can you NOT do as a Tenant
There is pretty little you cannot do.  If you're not sure, shoot us a message using our [Support](https://github.com/fiserv/support/issues).

## Directory of files
1. [FAQ](./faq.md)
2. [Glossary](./glossary.md)

## Developer Studio Demos
Checkout the [demo](./demo.md) page to see demos of our features.

## Below are the steps you need to follow:

1. #### Decide your integration level:
    * Full Service Tenant (Open API YAML file, Markdown Documentation and Live Sandbox Integration)
    * Doc Only Tenant (Open API YAML file, Markdown Documentation and [Prism Mock Server Integration](./enable-sandbox.md)
    * Linkout Tenant (External link to the Tenant Developer  Portal). [Basic Tenant Information](./tenant-basics.md)

3. #### Get your info together: 
    * Open API Spec file in YAML format (Version 3.0.0 and above)
    * Markdown Documentation, Product Description
    * Who is it for description and 1-3 UseCases/Popular Services.

5. #### Signup for a free [github](https://github.com) account:
    * Each tenant needs to register into github using their Fiserv email address and create an account. Once an account is created, please provide the Github username/registered email address to Developer studio team/Tenant Advocate.

7. #### It would help to use Stoplight or Swaggerhub Editor to edit/debug your docs and spec contents.
     * Swagger at https://fiserv-portal.stoplight.io/
     * Spotlight at https://editor.swagger.io/
     
5. #### A tenant advocate is assigned who would act as a Github admin to help the tenant get started. 

7. #### Wait for your tenant space to be provisioned.

9. #### Submit your info to a Tenant Advocate by creating a github issue in [Support](https://bit.ly/DSonboard). 
    
1.  #### Minimum Required Documents: 
    * Getting started markdown file
    * API specification file (yaml)
    * 1-3 use case (1 use case with 1 related document and 1 related api)
    
2.  #### Structure of the Tenant Repository: The Tenant Advocate will create a repository under Fiserv Git account.    
    * Assets/ Images- Folders contain raw images, logos, pdf files etc. These are used to link into a markdown file to display on dev studio.
    * Config- folder has document explorer definition yaml file, product-layout yaml file, and tenant json file outlining the structure of documentation, doc tree and product page.
    * Docs- Contains all markdown files that gets displayed on documentation explorer part of Dev Studio. The documentation is captured in markdown format (.md file) only.
    * References- Contains all api yaml files that gets displayed on API explorer part of Dev Studio for one or more version. All API yaml files must contain a version number so that the right yaml is fetched. The same version number must be referenced in the tenant json file
    * Docignore files- files to be ignored- examples archived files
    
3.  #### Read up on how to use your space and modify content: [Configure Tenant](./configure-tenant.md)

4.  #### OpenAPI spec and API Explorer page
    * [OpenAPI Specification Document](https://swagger.io/specification/)
    * [API Explorer page](./api-explorer.md)
    * [How to enable sandbox](./enable-sandbox.md)

5.  #### Add content based on your integration level

    Once you're happy with your content create another github issue to get deployed into upper environments and production

    Refer to the table contents to the right to get more details about each step.
    
6.  #### Your GitHub contents would be validated to check for accuracy and any syntax error. Read more about this here: [GitHub validators](./validator/studio-validators.md)

## Getting Help
If you need help, spot bugs, need ehancments or just want to chat you've got some options below.

- [How to Get Support](./get-support.md)
- Bugs / Enhancements / Questions
  - Go to our [Support](https://github.com/fiserv/support/issues)
- Want to chat
  - Go to MS Teams and search for `Developer Studio from Fiserv`

Ok, let's get started!
