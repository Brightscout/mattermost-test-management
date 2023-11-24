---
# (Required) Ensure all values are filled up
name: "Mention all users in channel or GM"
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

1. Send the `all`/`channel`/`here` mention in the linked channel or GM in MM.
2. Navigate to the linked channel or GM in MS Teams.

**Step 2**

1. Send the `Channel name` or `everyone` mention in the linked channel or GM respectively in MS Teams.
2. Navigate to the linked channel or GM in MM.

**Expected**

The user should be able to view the `channel name` or `everyone` mention highlighted in the linked channel or GM on MS Teams. 
After step 2, the user should be able to view the `all` mention highlighted in the linked channel or GM on MM.