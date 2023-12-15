---
# (Required) Ensure all values are filled up
name: "Linking a channel on MM"
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

1. Click on the `Link a channel` button in the RHS of MS Teams sync plugin on MM.
2. Select the desired `Mattermost channel`, the desired `Microsoft team` and a desired `Microsoft channel` for the selected MS team in the `Link a channel` modal.
3. Click on `Link channels` button in the `Link a channel` dialog.

**Step 2**

1. Click on the `Link a channel` button in the RHS of MS Teams sync plugin on MM.
2. Click on the `cancel` or `x` button in the `Link a channel` dialog.

**Expected**

The desired channel should get linked and a toast message should be visible in the RHS of MS Teams sync plugin for successfull connection with updation in the list of linked channels on MM.
After step 2, the `Link a channel` dialog should close and the RHS should persist it's state.