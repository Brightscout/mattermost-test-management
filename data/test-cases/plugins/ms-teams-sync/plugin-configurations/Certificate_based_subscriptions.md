---
# (Required) Ensure all values are filled up
name: "Certificate based subscription on MM"
status: Active
priority: Normal
folder: plugin-configurations
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

1. Add the `certificate public` and `certificate key` in the plugin settings on MM.
2. send message in the linked channel or DM/GM on MS Teams.
3. Navigate to the linked channel or DM/GM on MM.

**Step 1**

1. Remove the `certificate public` and `certificate key` in the plugin settings on MM.
2. send message in the linked channel or DM/GM on MS Teams.
3. Navigate to the linked channel or DM/GM on MM.

**Expected**

The user should be able to verify the message sync at more pace and their order in the linked channel or DM/GM on MM.
After step 2, the user should get a delay or there can be a mismatch in the order of the messages synced in the linked channel or DM/GM on MM.