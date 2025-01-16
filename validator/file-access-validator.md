# File Access Validator

For tenants utilizing our [Gated Content](how-to-use-gated-content.md) feature, we require that this validator is enforced and successful. This validator ensures that the `config/file-access-definition.yaml` is configured to properly mark various files under `assets/files/` as being restricted access when users attempt to download it.

The yaml should be a list of objects containing the name, access level, and allowed groups for each document that you need to be gated.

```yaml
- filePath: "file1.pdf"
  access: private
  groups: []  # Only require login to download
- filePath: "file2.docx"
  access: private
  groups: [TEST_GROUP_RG] # Only for TEST_GROUP access (after email approval)
- filePath: "file3.xlsx"
  access: public  # Anyone can download, no permissions; Similar to using `[file.xlsx](download/assets/files/file3.xlsx)`
```

## File Access Checks

* `filePath` for each file must be defined
* File must be found under `assets/files/`
* File must be of supported type
  - [
    "doc",
    "docx",
    "gz",
    "md",
    "msi",
    "pdf",
    "png",
    "ppt",
    "pptx",
    "txt",
    "xls",
    "xlsx",
    "zip"
  ]
* `access` level must be defined as either `private` or `public`
* If `private`, `groups` must be defined (either empty or with various group names)


## File Access Validator Job

![File Access Validator](/assets/images/validators/file-access-validator.png)

## File Access Validator failed Activity
This will list the failures along with the failed filename. In this screenshot example, various files listed in the `file-access-definition.yaml` have one or more errors associated. 

We'll try to print all the validation errors for each files but it does get cluttered and may need multiple runs to properly validate every overlapping check.

![Validator failures](/assets/images/validators/failed-file-access-validator-activity.png)

**Help:** Please connect with DevStudio team for more information and questions related with Validators via our Teams channel.
