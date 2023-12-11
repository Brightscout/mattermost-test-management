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

1. Click on the `Disconnect button` in the RHS of MS Teams sync plugin, when the channels are linked from MM to MS Teams .
2. Click on the `Disconnect button` in `Disconnect Microsoft Teams Account` modal on MM.

**Expected**

The user should be able to see the request message to `connect your account` with the list of linked channels in the RHS.