# Upload S3 Artifact
```yaml
- uses: aquacloud-dev/upload-artifact-action@main
  with:
    aws_access_key_id: ${{ secrets.AWS_ACCESS_KEY_ID }}
    aws_secret_access_key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
    aws_region: ${{ secrets.AWS_REGION }}
    bucket: ${{ secrets.S3_BUCKET_NAME }}
    path: /${{ github.sha }}
    source: .next,public
    context: .
```

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
