---
# (Required) Ensure all values are filled up
name: "Mention a single user in channel or DM/GM"
status: Active
priority: Normal
folder: mentions
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

1. Send mention for a user in the linked channel or DM/GM on MM.
2. Navigate to the linked channel or DM/GM on MS Teams.

**Step 2**

1. Send mention for a user in the linked channel or DM/GM on MS Teams.
2. Navigate to the linked channel or DM/GM on MM.

**Expected**

The user should be able to view the mentioned user highlighted in the linked channel or DM/GM on MS Teams. 
After step 2, the user should be able to view the mentioned user highlighted in the linked channel or DM/GM on MM.