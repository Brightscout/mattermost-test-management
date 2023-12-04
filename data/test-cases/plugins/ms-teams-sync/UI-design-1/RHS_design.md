---
# (Required) Ensure all values are filled up
name: "Validatin the RHS design"
status: Active
priority: Normal
folder: UI-design-1
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

1. When the App bar is enabled, click and open the RHS.

**Step 2**

1. When the App bar is disabled, click and open the RHS.

**Expected**

The user should be  able to view the RHS along with the App bar in the side on MM.
After step 2, the user should be able to view the RHS without App bar in the side and the MS Teams sync plugin icon in the channel header on MM.