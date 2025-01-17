# Glossary
Some commonly used terms you may hear us refer to around Teams, Github, or on various planning calls.

### Customers / Users
People (mainly developers) from businesses such as Home Depot or Bank of America who come to DevStudio to view/review API documentation and check release notes for products they have integrated with or would like to integrate into their business.

### Deployment
We follow a sprint-based AGILE process where we deploy code to `QA` after 2 weeks, `stage` the week after, and `production` the week after that (if no issues found during testing and staging). You only need to track deployment if changes to your product has been slated in a certain sprint.

Please note that for document and API spec changes on Github, you do not have to wait for deployment.

### [Environment](studio-environments.md)
Developer Studio has 4 environments where code and product content are deployed. For tenant knowledge, it is only necessary to know how their Github changes are mapped to each environment (other than when they need to be promoted to the upper environment for general public access).

  Github -> Developer Studio
  * develop -> qa-developer.fiserv.com
  * stage -> stage-developer.fiserv.com
  * main -> developer.fiserv.com (publicly available)
  * preview -> All 3 environments

### Indexing / Reindexing
Your API specs are hosted on elasticsearch and are reindexed on a regular basis (see [Search](search.md#frequency-of-updates) for more details). It is possible for our DevOps team to manually trigger a reindexing and we often do it right after an environment deployment occur. However, until an indexing job is ran on an environment, your new API changes will not reflect on the DevStudio site.

This process may change in the very near future as we continue to develop our webhooks and improve our caching/storage infrastructure.

### Sprint
AGILE 2 week long work period. Code changes happen constantly on our internal `dev` environment during these two weeks and some will be deployed afterward to `qa` and upper environments. These code changes affect website functionality and features, though for tenants most importantly it may contain needed backend changes to our database such as if you need to be promoted, change name, or change sandbox configuration (prism vs live, URL, auth, etc.).

### Tenant / Product
Is a product team that onboards their documentation and APIs onto the Fiserv Developer Portal (aka DevStudio, our Project PORTAL) for business developers to browse and view. For example, Commerce Hub or Clover.

### Tenant Advocate
These are members of the Developer Studio team who have Github and Teams admin access who will assist in answering various questions about the integration or issues, along with responding to and assigning Github requests to appropriate team members to discuss, design, and implement.

The member is on a rotation basis and changes from week to week (usually in a 2 week sprint cycle). As such, please utilize the official channels such as Teams and Github request to keep the conversation and request in a trackable/shareable space to facilitate hand-off and efficient communication instead of using private messages or pings.

### Webhook
Github webhook allows your PRs to trigger DevStudio internal API endpoints to immediately trigger updates on our database and storage servers. It has a rule setup to process any **push** request coming in and on our backend service, the proper branch (develop, stage, main) will automatically pick up and update for the corresponding environmental cache.

This webhook is protected by Github signature and other security measures to ensure it cannot be maliciously triggered. The endpoint itself can be also be ran by our DevOps team to manually update all of a tenant's files should something go wrong.

Currently, it allows near real-time update for all markdown files and tenant configuration files (`tenant.json`, `product-layout.yaml`, and `document-explorer-tree.yaml`).

### [Workspace](enable-workspaces.md)
We provide all DevStudio registered users (internal or external) the ability to create free workspaces which has access to the tenant's internal credential management system (such as Apigee) to provide users easy table management for free or paid API keys and CSRs.
