---
# (Required) Ensure all values are filled up
name: "Updated RHS after disconnecting a user from their account on MM"
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

1. Click on the `disconnect button` in the RHS of MS Teams sync plugin on MM.
2. Click on `disconnect button` in the `Disconnect Microsoft teams account` modal.

**Step 2**

1. Click on the `disconnect button` in the RHS of MS Teams sync plugin on MM.
2. Click on `cancel` button or `x` button in the `Disconnect Microsoft teams account` modal.

**Expected**

The user should be able to view the `connect account` button in the RHS with the toast message regarding the successful disconnection of the user account on MM.
After step 2, the `Disconnect Microsoft teams account` modal should close and the connection of user should not get affected.