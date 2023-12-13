---
# (Required) Ensure all values are filled up
name: "RHS updates after unlinking all channels"
status: Active
priority: Normal
folder: ui-integration-phase-2
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

1. Unlink all the linked channels from the `list of linked channels` on MM from RHS of MS Teams sync plugin.

**Expected**

The `list of linked channels` should be empty and the user should be able to see the `Link a channel` button in the RHS of MS Teams sync plugin on MM.