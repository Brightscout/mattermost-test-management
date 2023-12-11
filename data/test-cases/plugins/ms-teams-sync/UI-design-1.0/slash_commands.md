---
# (Required) Ensure all values are filled up
name: "RHS changes with respect to slash commands"
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

1. Connect the user to their MS Teams account using the `/msteams connect` slash command.
2. Click and open the RHS.

**Step 2**

1. Disconnect the user from their MS Teams account using the `/msteams disconnect` slash command.
2. Click and open the RHS.

**Expected**

The user account on MM should get connected to the account on MS Teams in the RHS on MM.
After step 2, the user should be able to view the `Connect your Microsoft Teams account` modal in the RHS on MM and the account should get disconnected.