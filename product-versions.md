# Product Versions

Product and API Versioning has been enabled to view Active, Preview, and Previous versions of the product.

### The purpose of creating branch versions is to:

 - Support the concept of technical preview.
 - Simplify the indexing mechanism (for develop and archive branches only).
 - Create reliable mechanism to view old/archived versions of tenant files.

![product versions](assets/images/product-versions.png)

### Version git Branches

  * ACTIVE - Main source of current state of documents and APIs
  * PREVIEW - Tech-preview branch to be merged into develop branch, for users to check upcoming WIP documentation and API changes; This branch is synced across all of DevStudio environments
  * PREVIOUS - Archived branch previously released from develop, rarely used but can be maintained for historical data if API version does not suffice for version control; This branch is synced across all of DevStudio environments

![version branches](assets/images/version-branches.png)
