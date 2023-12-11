---
# (Required) Ensure all values are filled up
name: "Error while unlinking a channel on MM"
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

1. Any Error occured while unlinking a channel on MM.
2. Click on `Try Again` button in the `unlink error` modal.

**Step 2**

1. Any Error occured while unlinking a channel on MM.
2. Click on `Cancel` or `x` button in the `unlink error` modal.

**Expected**

The same channel unlinking should again start.
After step 2, the unlinking should abort and the `unlink error` modal should close.