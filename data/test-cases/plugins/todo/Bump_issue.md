# (Required) Ensure all values are filled up
name: "Accept ToDo"
status: Active
priority: Normal
folder: ToDo
authors: "@AayushChaudhary0001"
team_ownership: 
- Change Team Name
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

1. Provide the authtoken of the user to whom the ToDo is assigned.
2. Provide the id of the ToDo from the list of the user to whom the ToDo is aasigned.

**Expected**

The desired ToDo should get accepted.