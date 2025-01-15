# Markdown Linter

As a way to provide tenants with some feedback for their markdown document cleanliness and readability, we have integrated a linter Github Action to help highlight some common markdown standards defined by the community.

The standards (and hence any linting errors you may encounter from the job) can be found [here](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md).

As this is not a functionally vital part of DevStudio, this validator will never be enforced or block your merge process, it is just there to warn you that your markdown document could be prettier.

Please feel free to reach out to us on Teams or Github if you have any suggestions on rules that we should ignore due to feasibility, usefulness, or otherwise!

## Markdown Linter Job

Please note that there is **no** `Required` tag, indicating that it will not block you even when failed.
![Git Action](/assets/images/validators/markdown-linter.png)


## Markdown Linter Successful Activity

Checking every single markdown file. Once validated logs will display name of the markdown file and status.
![Git Action](/assets/images/validators/markdown-linter-pass.png)


## Markdown Linter failed Job

![Git Action](/assets/images/validators/failed-markdown-linter-action.png)


## Markdown Linter failed Activity

Lists failed lint rules. For more information/example to help you fix them, please refer to the [linter documentation](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md).
![Git Action](/assets/images/validators/failed-markdown-linter-activity.png)

**Help:** Please connect with DevStudio team for more information and questions related with Validators via our Teams channel.
