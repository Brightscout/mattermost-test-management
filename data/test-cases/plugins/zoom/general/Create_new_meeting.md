---
# (Required) Ensure all values are filled up
name: "Click on Create new meeting when a meeting was already created."
status: Active
priority: Normal
folder: General
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

1. Connect the Zoom account to your MM account.
2. Create a Zoom meeting by slash command `/zoom start <meeting topic>` in any desired channel or DM/GM on MM.
3. Again run the slash command `/zoom start <meeting topic>` in the desired channel or DM/GM on MM.
4. Click on the `Create new meeting` option in the slack attachment for Zoom meeting in the desired channel or DM/GM on MM.

**Step 2**

1. Connect the Zoom account to your MM account.
2. Create a Zoom meeting by clicking on the zoom icon in the app bar in any desired channel or DM/GM on MM.
3. Again click on the zoom icon in the app bar in the desired channel or DM/GM on MM.
4. Click on the `Create new meeting` option in the slack attachment for Zoom meeting in the desired channel or DM/GM on MM.

**Step 3**

1. Create a new meeting by clicking on the `Create new meeting` option in the slack attachment for zoom meeting in any desired channel or DM/GM on MM.
2. Again navigate to the desired channel or DM/GM on MM without ending the meeting on Zoom and click on the `Create new meeting` option on the slack attachment.

**Expected**

The user should get redirected to the new zoom meeting or should get a slack attachment for selecting the meeting ID in the desired channel or DM/GM on MM.
After step 2, the user should get redirected to the new zoom meeting or should get a slack attachment for selecting the meeting ID in the desired channel or DM/GM on MM.
After step 3, the user should get redirected to the new zoom meeting or should get a slack attachment for selecting the meeting ID in the desired channel or DM/GM on MM.