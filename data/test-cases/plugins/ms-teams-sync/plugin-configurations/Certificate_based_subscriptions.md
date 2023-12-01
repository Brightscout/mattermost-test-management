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

1. When the `certificate based subscriptions` are enabled send message in the linked channel or DM/GM on MM or MS Teams.
2. Navigate to the linked channel or DM/GM on MS Teams or MM respectively.

**Step 1**

1. When the `certificate based subscriptions` are disabled send message in the linked channel or DM/GM on MM or MS Teams.
2. Navigate to the linked channel or DM/GM on MS Teams or MM respectively.

**Expected**

The user should be able to verify the message sync and their order in the linked channel or DM/GM on MS Teams or MM respectively.
After step 2, the user should get a delay or the order is not maintained for the messages sync in the linked channel or DM/GM on MS Teams or MM respectively.