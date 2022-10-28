# DevStudio Github Validator

Dev Studio have developed validation technique for all Tenant Github content. Validation is performed to validate and test Tenant's various files such as API specs file , markdown files , document explorer defination ,Tenant.json files and more. Validation check at Github repository helps Studio team to maintain and preserve standards and rules within the Tenant managed content.

# Validator 'Github Workflow' powered by Github Action

Studio validators are powered by Github Actions. 

## Github Action and workflow

Github Action is an in-buit platform by Github for continous integration and continious developement. Studio Validators developed over Github workflows triggered by Github events such as Pull Request created or Commit on feature branch(s).

## Available Validator

  * API Specification YAML file Validator
  * Markdown Validator
  * Documentation explorer defination
  * Tenant configuration file


## Navigating to Validator
 Every Dev Studio is configured with Validator. To navigate github action please follow steps. 

1. Navigate to Tenant Github Repository

2. Click on Actions from Top Menu option

![Git Action](../images/action-path.png)

3.List of Actions workflow

![Git Action Overview](../images/overview-actions.png)

4. Select latest workflow run
 
In order to see activity about the latest workflow job.

![Git Action workflow](../images/workflow-job.png)

5. List of triggered Job

![Git Action Jobs](../images/action-jobs.png)

6. Activity from the Job

![Git Action Job Activity](../images/action-job-activity.png)


