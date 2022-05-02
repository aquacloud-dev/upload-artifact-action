# Upload S3 Artifact
<!-- action-docs-description -->
## Description

Upload an artifact to S3


<!-- action-docs-description -->

<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| - | - | - | - |
| bucket | S3 bucket | `true` |  |
| path | S3 path | `false` |  |
| source | Source directory | `true` |  |
| aws_region | S3 region | `true` |  |
| aws_access_key_id | AWS Access Key ID | `true` |  |
| aws_secret_access_key | AWS Secret Access Key | `true` |  |
| context | Context directory | `false` | . |

> NOTE: Make sure to add a `/` at the start of the `path` argument.


<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is an `composite` action.


<!-- action-docs-runs -->

