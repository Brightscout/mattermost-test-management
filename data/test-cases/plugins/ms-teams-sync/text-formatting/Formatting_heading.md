---
# (Required) Ensure all values are filled up
name: "Formatting text as headings"
status: Active
priority: Normal
folder: text-formatting
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
playwright: nulla
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

1. Enter the text in the text area in channel or DM/GM on MM.
2. Select the desired text and click on heading button.
3. Click on the send button in MM.
4. Navigate to the linked channel or DM/GM on MS teams.

**Step 2**

1. Enter the text in the text area in channel or DM/GM on MS teams.
2. Select the desired text and select the heading type from the rich style dropdown.
3. Click on the send button in MS teams.
4. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the text in the applied heading format on MS teams. After step 2, the user should be able to view the text in the applied heading format on MM.