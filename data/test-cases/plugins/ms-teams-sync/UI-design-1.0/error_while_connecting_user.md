---
# (Required) Ensure all values are filled up
name: "RHS changes for error in connecting the user"
status: Active
priority: Normal
folder: UI-design-1.0
authors: "@arush-vashishtha"
team_ownership: []
priority_p1_to_p4: P2 - Core Functions (Do core functions work?)

# (Optional)
location: null
component: null
tags: []
labels: []
tested_by_contributor: null

# (Optional) Test type and tools
cypress: null
detox: null
mmctl: null
playwright: null
rainforest: []
manual_test_environments: []

# Do not change
id: null
key: null
created_on: null
last_updated: null
case_hashed: null
steps_hashed: null
---

**Step 1**

1. Any error occured while connecting the user to their MS Teams account.

**Expected**

The user should be able to view the `Connect your Microsoft Teams account` modal in the RHS with the toast message regarding the failure of the connection due to any error on MM.