---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "coder_external_auth Data Source - terraform-provider-coder"
subcategory: ""
description: |-
  Use this data source to require users to authenticate with an external service prior to workspace creation. This can be used to pre-authenticate external services in a workspace. (e.g. gcloud, gh, docker, etc)
---

# coder_external_auth (Data Source)

Use this data source to require users to authenticate with an external service prior to workspace creation. This can be used to pre-authenticate external services in a workspace. (e.g. gcloud, gh, docker, etc)



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) The ID of a configured external auth provider set up in your Coder deployment.

### Read-Only

- `access_token` (String) The access token returned by the external auth provider. This can be used to pre-authenticate command-line tools.