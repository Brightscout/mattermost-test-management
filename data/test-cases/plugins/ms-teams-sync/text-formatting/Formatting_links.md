---
# (Required) Ensure all values are filled up
name: "Formatting text as links"
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

1. Enter text in the text area of the channel or DM/GM in MM.
2. Select the desired text and click on link button in formatting menu.
3. Enter the url in the '()' in text area.
4. Click on send button in MM.
5. Navigate to the linked channel or DM/GM in MS teams.

**Step 2**

1. Enter text in the text area of the channel or DM/GM in MS teams.
2. Select the desired text and click on insert link button.
3. Enter the address in the insert link modal and click on insert.
4. Click on send button in MS teams.
5. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the text as hyperlink in MS teams. After step 2, the user should be able to view the text as hyperlink in MM.