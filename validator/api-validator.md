# API Specification File Validator

Most of Dev Studio tenant are API enabled tenants. In order to protect Dev Studio and maintain standards amoung all Dev Studio tenants. Tenants are configured with API validator. 

## API Validation Check Rules

- Valid YAML Spec 3.0 Standard (with proper fields)
- Must include `x-proxy-name` for api(s)
- Checks all APIs being used under `tenant.json - apiVersions`
- Will be adding more.....

## API Validator Job

![Git Action](/assets/images/validators/api-validator.png)

![Git logs](/assets/images/validators/api-spec-validator-activity.png)

## API Validator Successful Activity

Checking every single API. Once validated logs will display name of the spec file and status.

![Git Action](/assets/images/validators/api-validator-pass.png)

## API Validator failed Job

![Git Action](/assets/images/validators/failed-api-validator-action.png)

## API Validator failed Activity

Checking every single API. Once validated logs will display name of the spec file and status.

![Git Action](/assets/images/validators/failed-api-validator-activity.png)

Help: Please connect with DevStudio team for more information and questions related with Validators via our Teams channel.
