# Markdown File Validator

In order to protect Dev Studio and maintain standards amoung all Dev Studio tenants, tenants are configured with markdown validator. 

## Markdown Validation Check Rules

- Valid markdown file extension and formatting
- Links to downloadable files and embedded images should link to respective files in the Github repository
  - Images should be embedded such as `![image name](/assets/images/validators/image.png)`
  - Downloadable docs should be formatted as `[downloadable file](download/assets/files/download.zip)`
- Files/images being linked to should exist in repository


## Markdown Validator Job

![Git Action](/assets/images/validators/markdown-validator.png)


## Markdown Validator Successful Activity

Checking every markdown file. Once validated logs will display name of the markdown file and status. 
![Git Action](/assets/images/validators/markdown-validator-pass.png)


## Markdown Validator failed Job

![Git Action](/assets/images/validators/failed-markdown-validator-action.png)


## Markdown Validator failed Activity
This will list the failures along with the failed filename.
![Git Action](/assets/images/validators/failed-markdown-validator-activity.png)

**Help:** Please connect with DevStudio team for more information and questions related with Validators via our Teams channel.
