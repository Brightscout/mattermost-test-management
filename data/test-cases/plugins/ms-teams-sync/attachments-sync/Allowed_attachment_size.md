---
# (Required) Ensure all values are filled up
name: "Allowed size of attachment"
status: Active
priority: Normal
folder: attachments-sync
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

1. Click on the attachments button in channel or DM/GM in MM.
2. Select the attachment of the allowed size and click on open.
3. Click on the send button in MM.
4. Navigate to the linked channel or DM/GM in MS teams.

**Step 2**

1. Click on the attachments button in channel or DM/GM in MS teams.
2. Select the attachment of the allowed size and click on open.
3. Click on the send button in MS teams.
4. Navigate to the linked channel or DM/GM in MM.

**Expected**

The user should be able to view the attachment in MS teams. After step 2, the user should be able to view the attachment in MM.