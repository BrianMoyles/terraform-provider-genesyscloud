---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "genesyscloud_task_management_workbin Data Source - terraform-provider-genesyscloud"
subcategory: ""
description: |-
  Genesys Cloud task management workbin data source. Select an task management workbin by name
---

# genesyscloud_task_management_workbin (Data Source)

Genesys Cloud task management workbin data source. Select an task management workbin by name

## Example Usage

```terraform
data "genesyscloud_task_management_workbin" "example_workbin" {
  name = "My Workbin"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) task management workbin name

### Read-Only

- `id` (String) The ID of this resource.