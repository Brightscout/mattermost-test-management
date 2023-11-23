---
# (Required) Ensure all values are filled up
name: "Formatting text as headings"
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

1. Enter and select the text in the text area in linked channel or DM/GM on MM.
2. Click on heading button and then click on the send button in MM.
3. Navigate to the linked channel or DM/GM on MS Teams.

**Step 2**

1. Enter and select the text in the text area in linked channel or DM/GM on MS Teams.
2. Select the heading type from the rich style dropdown and click on the send button in MS Teams.
3. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the text in the applied heading format in the linked channel or DM/GM on MS Teams. 
After step 2, the user should be able to view the text in the applied heading format in the linked channel or DM/GM on MM.