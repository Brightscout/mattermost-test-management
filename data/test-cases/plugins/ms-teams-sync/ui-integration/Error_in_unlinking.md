---
# (Required) Ensure all values are filled up
name: "Error while unlinking a channel on MM"
status: Active
priority: Normal
folder: ui-integration
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

1. Any error occured while unlinking a channel from RHS of MS Teams sync plugin on MM.

**Step 2**

1. Any error occured while unlinking a channel from RHS of MS Teams sync plugin on MM.
2. Click on `Try Again` button in the `unlink error` dialog.

**Step 3**

1. Any error occured while unlinking a channel from RHS of MS Teams sync plugin on MM.
2. Click on `Cancel` or `x` button in the `unlink error` dialog.

**Expected**

The `unlink error` modal should open on MM.
After step 2, unlinking should again start for the same channels on MM.
After step 3, the unlinking should abort and the `unlink error` dialog should close and the RHS of MS Teams sync plugin should persist it's state.