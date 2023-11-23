---
# (Required) Ensure all values are filled up
name: "Formatting text with markdown"
status: Active
priority: Normal
folder: text-formatting
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

1. Enter text within "``" in the text area of the linked channel or DM/GM and click on send button in MM.
2. Navigate to the linked channel or DM/GM in MS Teams.

**Step 2**

1. Enter text within "``" in the text area of the linked channel or DM/GM and click on send button in MS Teams.
2. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the text in a white background box in linked channel or DM/GM on MS Teams. 
After step 2, the user should be able to view the text in a grey background box in linked channel or DM/GM on MM.