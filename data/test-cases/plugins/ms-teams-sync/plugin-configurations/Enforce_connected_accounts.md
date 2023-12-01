---
# (Required) Ensure all values are filled up
name: "Enforce connected account page"
status: Active
priority: Normal
folder: plugin-configurations
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

1. When the `enforce connected account` option is true and the disconnected user log-in into their account on MM.

**Step 2**

1. When the `enforce connected account` option is true and `Allow to temporarily skip connect user` is true and the disconnected user log-in into their account on MM.
2. The user click on `Skip for now` option.

**Expected**

The enforce connect page should open and the user should get the option to connect their account to MS Teams.
After step 2, the user should get directed to their MM account.