# Config Validator

This validator checks various `config` files and links within your tenant repository for valid structure and linking between various components.

## Config Validation Check Rules

- All three config files are present and properly formatted
- File references (such as apiVersion, getStartedFilePath, resourcesFilePath, etc.) all lead to an existing and valid file in your repository
- Files listed in doc-tree exist and accessible

### Tenant config checks
Ensure existence of the following fields/definitions:

- `product.description`: String; 0 < length < 112 characters
- `getStartedFilePath`: String
- `resourcesFilePath`: String (optional)
- `solution`: List
- `apiVersion`: List
- `apiVersion.?.releaseNotesPath`: String (release note MD for each apiVersion defined)
- `apiVersion.?.version`: Check that there is 1 MIN/MAX `major` (latest) apiVersion

## Config Validator Job

![Git Action](/assets/images/validators/config-validator.png)


## Config Validator Successful Activity

Checking every single API. Once validated logs will display name of the markdown file and status.

![Git Action](/assets/images/validators/config-validator-pass.png)


## Config Validator failed Job

![Git Action](/assets/images/validators/failed-config-validator-action.png)


## Config Validator failed Activity

Display error logs for the various failures from the checks listed above

![Git Action](/assets/images/validators/failed-config-validator-activity.png)

**Help:** Please connect with DevStudio team for more information and questions related with Validators via our Teams channel.
