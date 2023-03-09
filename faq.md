# Frequently Asked Questions

* We like the organization and formatting of the Developer Studio site, are there templates that can be shared?
  * You provide the doc & apis & the Studio provides everything else.  You use regular markdown or our flavor of markdown to draft your documents. https://developer.fiserv.com/support/docs/?path=docs/md/basic-syntax.md

* Who is eligible to post their APIs on the Developer Studio?
  * Anyone.  It’s for the whole company.

* What is the Developer Studio on-boarding process?
  * You can read about that here: github.com/fiserv/tenants-doc

* Do you have insight to the corporate vision for whether https://docs.firstdata.com/ and https://developer.fiserv.com will live on in parallel or eventually converge?
  * Will converge in the end.  For now, as we transition your content you’ll have both until you get enough feature parity and then you’ll shutdown the old portal.

* How can Tenants decide which solution/category they should choose? Does Devportal allow a Prodcut to reside on multiple solution areas?

* How can Tenants integrate their Products with Developer Studio?
   *
   
* How can Tenants segregate the product contents based on the customer segments?


* What do you mean by Available services & Popular services?
   * Available service means the range of the service/facilities the product provides.
   * Popular service means the frequently usd/demanded service/facilities of the product.


* How and where can Tenants provide tags for their product? is it in GitHub?
   * Dev Studio no longer support Beta tags.


* How can Tenants administer the GitHub repository?
   * Initially Tenant team will only have maintainer access. Once everything is more content within Tenant repo, Tenant Advocate should provide        githb repo admin access to Tenant Team maintainer. 


* How do Tenants get access to Prism Mock server and make them work?
  * Prism Mock Server is integrated within Dev Studio architecture. Tenant won't have any access to Prism Mock Server. Tenant developer can test Prism       mock server functionality by installing on development machine via https://github.com/stoplightio/prism. 

* How do Tenants integrate their contents with Live Server?
  

* Is there a way to hide/exclude documentations from showing up on the UI?
  * Tenant can use `.docignore` File present in every tenant github repository. By just passing the path of the .md file(s), tenant can exclude from showing up on the UI. 

* How does one generate the API keys?


* How can one get access to the CI/CD pipelines?


* How much time does it take to reflect the docs and APIs? How often does the content get refreshed in production environment?
  * Updated documents are refelcted immediately via Github webhooks.
  * APIs are updated on different interval per environment.
     - PROD ( On Production deployment day)

* Can we automate so that new APIs get discovered?


* Is there a way to quickly convert my swagger 2.0 specs to OpenAPI spec?


* Is the doc tree or API explorer cached?
  * Doc tree is cached in redis
  * Api Explorer is cached in Elastic


* Why few images are not loaded on UI.
  * Some images are not uploaded temp links are associated and the repo maybe private. Hence use permanent links while uploading images if the Repo is private.

* How to upload an image using a relative link in the same repo?
  * You can use this link to verify  https://stackoverflow.com/questions/7653483/github-relative-link-in-markdown-file


* What  images are accepted in Github
  * https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files
 

* How do we link a GitHub repo/file so it’s downloadable in Dev Studio
  * At the moment you can download the API specifications as a zip file and also as a postman collection from Dev Studio UI.

