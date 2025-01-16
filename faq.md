# Frequently Asked Questions

### We like the organization and formatting of the Developer Studio site, are there templates that can be shared?
  * We provide basic markdowns and sample API yamls in a preferred structure when first providing you with a repository. You use regular markdown or our flavor of markdown to draft your documents. https://developer.fiserv.com/support/docs/?path=docs/md/basic-syntax.md

### Who is eligible to post their APIs on the Developer Studio?
  * Anyone. It's for the whole company.

### What is the Developer Studio on-boarding process?
  * You can read about that here: [github.com/fiserv/tenants-doc](https://fiserv.gitbook.io/tenant-docs/)

### Do you have insight to the corporate vision for whether https://docs.firstdata.com/ and https://developer.fiserv.com will live on in parallel or eventually converge?
  * Will converge in the end. For now, as we transition your content you'll have both until you get enough feature parity and then you'll shutdown the old portal.

### How can Tenants decide which business type they should choose? Does Devportal allow a Product to reside on multiple business types?
  * Yes, you may select as many business types as you feel like your product reaches. These tags will help businesses and customers apply as filters when searching for a solution to fit their needs.

### How can Tenants integrate their Products with Developer Studio?
  * Have a GitHub account with your Fiserv email. (https://github.com/Fiserv)
  * To request an onboarding you can fill out the [Onboarding form](https://github.com/Fiserv/Support/issues/new?assignees=russnicoletti%2Cminh-pham1&labels=Onboard+New+Tenant&projects=&template=onboard_new_tenant.yml&title=Onboard+a+new+tenant) - and provide all the information/requirements  to on board your product. On-boarding Form
  * Please go through our Tenant document https://fiserv.gitbook.io/tenant-docs/ which will provide all the info you need to get going to onboard into the Developer Studio. 

### How can Tenants segregate the product contents based on capabilities and/or business type?
  * Currently, all content in a product will be automatically labeled the same as the main product's tags. This way, when a user searches for certain keywords and filters, it'll still narrow down to approximately the same content and hence product.

### What do you mean by Available services & Popular services?
  * Available service means the range of the service/facilities the product provides.
  * Popular service means the frequently usd/demanded service/facilities of the product.

### How and where can Tenants provide tags for their product? is it in GitHub?
  * You can request it to be added via Github Ticket. However, most of our `beta` tenants refer to experiment products with documentation and APIs revolving around new AI or innovation trends rather than just products whose documentation are still WIP.

### How can Tenants administer the GitHub repository?
  * Initially Tenant team will only have write access. Once everything is more content within Tenant repo, Tenant Advocate may provide github repo maintainer access to Tenant Team upon request and proper justification. This is for security and standardization reasons to ensure content is properly validated and secured within DevStudio.

### How do Tenants get access to Prism Mock server and make them work?
  * Prism Mock Server is integrated within Dev Studio architecture. Tenant won't have any access to Prism Mock Server. Tenant developer can test the Prism mock server functionality by installing on development machine via https://github.com/stoplightio/prism.

### How do Tenants integrate their contents with Live Server?
  * Upon making onboarding request or at any time via Github issue, the tenant may inform the Developer Studio team that they would like to use a Live Server (i.e. provide their own externally hosted sandbox endpoint to process mocked requests on azure/aws/etc.) at which point a DevStudio team member will ask via secure channels for the endpoint details, authentication protocol, and authentication information. Once changes are made, any `Run Request` operations from DevStudio site will send a call to the endpoint and return the response back.
  
### Is there a way to hide/exclude documentations from showing up on the UI?
  * Tenant can use `.docignore` File present in every tenant github repository. By just passing the path of the .md file(s), tenant can exclude from showing up on the UI. 

### How does one generate the API keys?
  * Please follow the guide under [Workspace management](enable-workspaces.md#manage-workspace)

### How can one get access to the CI/CD pipelines?
  * You can click on `Actions` at the top of Github to view recently executed validators and post-merge pipelines. Only DevStudio team members can change them though we greatly appreciate any comments or concerns about them. Please feel free to reach out to us on our Teams channel or via Github Issue ticket to send these comments or request for additional functionalities.

### How much time does it take to reflect the docs and APIs? How often does the content get refreshed in production environment?
  * Updated documents are refelcted immediately via Github webhooks.
  * APIs are updated on different interval per environment. Please check under [Frequency of updates](search.md#frequency-of-updates)

### Can we automate so that new APIs get discovered?
  * While we have no process for this, `release-notes` is the primary way for standard practice and you may also change the Featured API on your `product-layout` which defines the homepage of your product.

### Is there a way to quickly convert my swagger 2.0 specs to OpenAPI spec?
  * There are various packages/services such as `swagger2openapi` and `swagger-api/swagger-converter` which can handle this. We don't offer it natively without DevStudio at the current moment.

### Is the doc tree or API explorer cached?
  * Doc tree is cached in redis
  * API explorer is cached in Elastic

### Why few images are not loaded on UI.
  * Make sure you are using the correct format for images such as `![image name](/assets/images/<image_link>.png)` and the image is hosted in your local github repo

### How to upload an image using a relative link in the same repo?
  * Simply add the image file to the `assets/images` directory in your repository as per usual Git process and link to it from any markdown document using the syntax `![image name](/assets/images/<image_link>.png)`. HTML such as `<img src="/assets/images/<image_link>.png"/>` will also work.

### What images are accepted in Github
  * https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files
 
### How do we link a GitHub repo/file so it's downloadable in Dev Studio
  * Add the image file to the `assets/files` directory in your repository as per usual Git process and link to it from any markdown document using the syntax `[filename](download/assets/images/<filename>)`. HTML such as `<a href="download/assets/files/<filename>" download>downlad link</a>` will also work. The `download/` prefix will be parsed by our backend service to fetch from your Github using a secret Github token for security.

### What are the various product access associated in Developer Studio?
  * Internal: These products can only be accessed when a user is logged in with a Fiserv email account. These products contain Fiserv internal APIs and documents
  * Semi-public: Mostly normal product with some document downloads that require approval. See [Gated content](how-to-use-gated-content.md).
  * Public: Normal products with or without an API explorer. Available for viewing by all users with or without sign-in on production environment at developer.fiserv.com
  * Workspace enabled: Some products (internal or public) also can have a workspace to host their API keys and/or other credentials fetched from the product team's own Apigee (or other credential management) system. This integration requires a lot more planning and would require attendance at a Partner Planning Call with Alvin Cho for further explanation and discussion.

### How do I or my team member(s) get Write access to our product's Github repository?
  * Please send the request with the person's Github ID or email along with the repository in question to either our Teams channel or a Github Issue.
