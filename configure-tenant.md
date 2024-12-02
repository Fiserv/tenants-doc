# How to use your space and modify your content.

### Required repository structure:

![repository structure](assets/images/repo-file-structure.png "repository structure")


### Git branches
There are **three branches** that are required:
  - `develop` corresponds to [develop/qa environments](https://dev-developer.fiserv.com)
  - `stage` corresponds to [stage environment](https://stage-developer.fiserv.com)
  - `main` corresponds to [production environments](https://developer.fiserv.com)

![git branches](assets/images/gitHubBranches.png "git branches")


### Configurations files 
Files under **config** directory define tenant/product setup, documentation tree, product page data.

![config files](assets/images/config-files.png "config files")


**config/document-explorer-definition.yaml** defines documetation tree on left navigation panel

![doc tree](assets/images/docs-tree.png "doc tree")


**config/product-layout.yaml** defines product page content

![product page](assets/images/product-layout.png "product page")


**config/tenant.yaml** defines product configuration such as 
  - name, 
  - industry or solution. Tenant is able to belong to multiple solutions.
  - API version, 
  - featured branches, 
  - sandbox features, 
  - support contact for tenant specific issues.

![tenant config](assets/images/tenant-config.png)
![api version](assets/images/api-version.png)
