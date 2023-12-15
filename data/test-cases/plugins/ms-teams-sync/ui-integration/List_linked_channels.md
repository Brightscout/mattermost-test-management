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

1. Click on MS Teams sync icon in App bar or channel header and open the RHS when there are MM channels liked to MS Teams channel.

**Step 2**

1. Click on MS Teams sync icon in App bar or channel header and open the RHS when there are MM channels liked to MS Teams channel and the logged in user is a normal user.

**Step 3**

1. Click on MS Teams sync icon in App bar or channel header and open the RHS when there are MM channels liked to MS Teams channel and the logged in user is a system admin.

**Expected**

The user should be able to see the `list of linked channels` in the RHS of MS Teams sync plugin on MM.
After step 2, the user should be able to see those linked channels in the `list of linked channels` in the RHS of MS Teams sync plugin in which they are added as a member on MM.
After step 3, the user should be able to see all the linked channels in the `list of linked channels` in the RHS of MS Teams sync plugin on MM.