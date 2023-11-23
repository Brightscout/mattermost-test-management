---
# (Required) Ensure all values are filled up
name: "Send multiple attachments"
status: Active
priority: Normal
folder: attachments-sync
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

1. Upload multiple attachments in linked channel or DM/GM in MM.
2. Click on the send button in the MM.
3. Navigate to the linked channel or DM/GM in MS Teams.

**Step 2**
1. Upload multiple attachments in linked channel or DM/GM in MS Teams.
2. Click on the send button in the MS Teams.
3. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view all the attachments in MS teams sent from MM. 
After step 2, the user should be able to view all the attachments in MM sent from MS Teams.