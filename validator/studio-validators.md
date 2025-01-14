# Github Validators from Developer Studio

The Developer Studio Team has developed a validation technique to ensure that all the contents added by the tenants in the GitHub repositories are accurate and to check for syntax problems. These validation checks help the team to maintain and preserve standards and rules within the Tenant managed content. The validation rules apply to the OpenAPI specification files, markdown files, document-explorer-definition.yaml, tenant.json files and more.


# Understanding Developer Studio Validators

Developer Studio validators are powered by GitHub actions.

## Github Actions and Workflows

GitHub Actions are individual tasks that you can combine to create jobs and customize your workflow. On the other hand, GitHub Workflows are custom automated processes that you can set up in your repository to build, test, package, release, or deploy any project on GitHub. Developer Studio Validators are developed using Github workflows that were triggered by Github events such as Pull Request or Commits on feature branches.

## Available Validators

  * OpenAPI Specification YAML file Validator
  * Markdown Validator
  * document-explorer-definition.yaml file validator
  * tenant-config.yaml file validator

## Navigating to Validators inside your repository

 Every tenant repository is configured with these validators. To navigate to github action please follow the below steps:

1. Navigate to Tenant Github Repository

2. Click on Actions from Top Menu option

![Git Action](/assets/images/action-path.png)

3. List of Actions workflow

![Git Action Overview](/assets/images/overview-actions.png)

4. Select latest workflow run
 
In order to see activity about the latest workflow job.

![Git Action workflow](/assets/images/workflow-job.png)

5. List of triggered Job

![Git Action Jobs](/assets/images/action-jobs.png)

6. Activity from the Job

![Git Action Job Activity](/assets/images/action-job-activity.png)


# Tenant's responsitbility when Validators throw errors

Tenant is responsible for responding when Validators throw errors for any GitHub content. To learn how keep reading.

## Validator Logs

All Github workflow generate output as a logs. Based on the success or failure of the Validation Job. Developers can browse through the logs to identify the issues within their content. 
Primary output of every validator is generated in individual Action Job output logs. 


### `Sucessful` Job Output: 

![Git Action Job Output](/assets/images/api-validator-pass.png)


### `Failed` Job Output:

![Git Action Job Output](/assets/images/action_error_logs.png)


## Resolve errors from the logs

To identify issues and fix the issues within Github content. Developer should go through validator output logs. Individual Logs explain what type error of encountered within particular file(s).



Please connect with Developer Studio team for more information and questions related with Validators. 
