---
# (Required) Ensure all values are filled up
name: "Mention all users in channel or GM"
status: Active
priority: Normal
folder: mentions
authors: "@AayushChaudhary0001"
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

1. In the text area mention "all" in the desired channel or GM on MM.
2. Click on the send button in MM.
3. Navigate to the linked channel or GM in MS teams.

**Step 2**

1. In the text area mention the "Channel" or "everyone" in the desired channel or GM respectively on MS teams.
2. Click on the send button in MS teams.
3. Navigate to the linked channel or GM in MM.

**Expected**

The user should be able to view the 'all' mention highlighted in the desired channel or GM on MS teams. After step 2, the user should be able to view the 'all' mention highlighted in the desired channel or GM on MM.