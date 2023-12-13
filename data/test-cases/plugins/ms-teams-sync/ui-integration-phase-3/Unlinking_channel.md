---
# (Required) Ensure all values are filled up
name: "Unlinking a channel on MM"
status: Active
priority: Normal
folder: ui-integration-phase-3
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

1. Hover over the desired row in the list of linked channels and click on unlink button on the row in the RHS of MS Teams sync plugin on MM.
2. Click on `unlink channels` button in the `Unlink channel` modal on MM.

**Step 2**

1. Hover over the desired row in the list of linked channels and click on unlink button on the row in the RHS of MS Teams sync plugin on MM.
2. Click on `cancel` or `x` button in the `Unlink channel` modal on MM.

**Expected**

The desired channel should be unlinked and the RHS of MS Teams sync plugin should get updated.
After step 2, the `Unlink channel` modal should close and the RHS of MS Teams sync plugin should persist it's state.