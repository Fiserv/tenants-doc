# Developer Studion environments

### Developer Studion has four environments

  - [dev](https://dev-developer.fiserv.com) - require authentication, generally only for DevStudio engineers to test experimental/non-finalized features
  - [qa](https://qa-developer.fiserv.com) - require authentication
  - [stage](https://stage-developer.fiserv.com) - require authentication
  - [production](https://developer.fiserv.com)


The main environments you will use for validating your tenant content will be the `qa` and `stage` environments which **require** authentication credentials. 
Your tenant advocate will provide these credentials via direct message on Teams once you have been onboarded.
In general **authentication credentials are not to be shared** with external clients. Please consult with your tenant advocate.

<img src="assets/images/signin-auth.png" alt="signin auth" style="max-width: 50%;" width="400">

### Git branches

There are **five git branches** that are utilized by DevStudio:

  - **develop** corresponds to [qa environments](https://qa-developer.fiserv.com)
  - **stage** corresponds to [stage environment](https://stage-developer.fiserv.com)
  - **main** corresponds to [production environments](https://developer.fiserv.com)
  
The following two branches are for product versioning which is shared across all environments

  - preview
  - previous


![git branches](assets/images/github/github-branches.png "git branches")


### Developer Studio Release Schedule 

Developer Studio is on a **two week** sprint schedule.
That means at the end of the sprint, every other Tuesday, dev code will be deployed to `qa`.
On the following Thursday (third week from the start of a sprint) qa code will be deployed to `stage`.
And finally on Thursday (fourth week from the start of a sprint) stage code is deployed to `production`.

Tenants who are requesting to be onboarded or promoted to higher environments are responsible for updating their respective Github branches to the latest information in time for deployment. If configurations or other content are invalid, this may cause a delay in our deployment and require us to disable the product until the issue is fixed on the next deployment date.