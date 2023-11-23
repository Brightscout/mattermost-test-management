---
# (Required) Ensure all values are filled up
name: "Formatting text with bold, italics and strikethrough features"
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

1. Enter and select the text in the text area of the linked channel or DM/GM in MM.
2. Click on bold button, italics button, and strikethrough button in formatting menu and then click on send button in MM.
3. Navigate to the linked channel or DM/GM in MS Teams.

**Step 2**

1. Enter and select the text in the text area of the linked channel or DM/GM in MS Teams.
2. Click on bold button, italics button, and strikethrough button and then click on send button in MS Teams.
3. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the text formated with bold, italics, and strikethrough in linked channel or DM/GM MS Teams. 
After step 2, the user should be able to view the text formated with bold, italics, and strikethrough in linked channel or DM/GM on MM.