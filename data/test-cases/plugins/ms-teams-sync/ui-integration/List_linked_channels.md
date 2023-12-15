---
# (Required) Ensure all values are filled up
name: "List of linked channels in RHS"
status: Active
priority: Normal
folder: ui-integration
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

1. Click on the MS Teams sync icon in the app bar or channel header to open the RHS when there are MM channels linked to the MS Teams channel and the logged-in user is a `member`.

**Step 2**

1. Click on the MS Teams sync icon in the app bar or channel header to open the RHS when there are MM channels linked to the MS Teams channel and the logged-in user is a `system admin`.

**Expected**

The user should be able to see the list of linked channels in the RHS of the MS Teams sync plugin in which they are added as a member in MM.
After step 2, the user should be able to see the list of all the linked channels in the RHS of the MS Teams sync plugin on MM.