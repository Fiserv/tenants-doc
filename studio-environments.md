# Developer Studion environments

### Developer Studion has four environments

  - [dev](https://dev-developerstudio.fiserv.com) - require authentication
  - [qa](https://qa-developerstudio.fiserv.com) - require authentication
  - [stage](https://stage-developerstudio.fiserv.com) - require authentication
  - [production](https://developer.fiserv.com)


dev, qa, stage evironment **require** authentication credentials. Your tenant advocate will provide them.
In general **authentication credentials are not to be shared** with external clients. Please consult with your tenant advocate.

<img src="assets/images/signin-auth.png" alt="signin auth" style="max-width: 50%;" width="400">

### Git branches

There are **five git branches** that are required:

  - **develop** corresponds to [develop/qa environments](https://dev-developerstudio.fiserv.com)
  - **stage** corresponds to [stage environment](https://stage-developerstudio.fiserv.com)
  - **main** corresponds to [production environments](https://developer.fiserv.com)
  
The following two branches are for product versioning

  - preview
  - previous


![git branches](assets/images/gitHubBranches.png "git branches")


### Developer Studio Release Schedule 

Developer Studio is on a **two week** sprint schedule.
That means at the end of the sprint, every other Friday, dev code will be deployed to qa.
On the following Thursday (third week of the start of the sprint) qa code will be deployed to stage.
And finally on Thursday (fourth week of the start of the sprint) stage code is deployed to production.


      The tenant is responsible for syncing up github repository in accordance with Developer Studio release schedule.
