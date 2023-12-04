---
# (Required) Ensure all values are filled up
name: "RHS changes after connecting the user on MM"
status: Active
priority: Normal
folder: UI-design-1
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

1. Connect the user to their MS Teams account from RHS.

**Expected**

The user should be able to see the `Link channel` modal in the RHS with a toast message regarding the successful connection of their account on MM.