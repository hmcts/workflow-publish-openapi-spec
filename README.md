# workflow-publish-openapi-spec

This reusuable workflow can be used to published OpenAPI specs to the [HMCTS CNP API repository](https://github.com/hmcts/cnp-api-docs).

## Usage

There's a workflow template at https://github.com/hmcts/.github/blob/master/workflow-templates/publish-openapi.yml.

To use it from your repository go to:

Actions -> New workflow

Click Configure under "Publish OpenAPI specs"

Update the `test_to_run` input variable
Check the `java_version` variable is right for your project
