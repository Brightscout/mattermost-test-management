---
# (Required) Ensure all values are filled up
name: "Error while linking a channel on MM"
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

1. Any error occured while linking a channel on MM.

**Step 2**

1. Any error occured while linking a channel on MM.
2. Click on `Try Again` button in the `Unable to link channels` modal.

**Step 3**

1. Any error occured while linking a channel on MM.
2. Click on `Cancel` or `x` button in the `Unable to link channels` modal.

**Step 4**

1. Connect the channel on MM to channel on MS Teams using slash command `/msteams-sync connect`.
2. Click on the MS Teams sync icon in App bar or channel header and open the RHS.
3. Click on link a channel and link the previously linked channel.

**Expected**

The `Unable to link channels` modal should open on MM.
After step 2, linking should again start for the same channels on MM.
After step 3, the linking should abort and the `Unable to link channels` modal should close and the RHS of MS Teams sync plugin should not update.
After step 4, The [modal name will be added] modal should open on MM.