---
# (Required) Ensure all values are filled up
name: "Error after linking a channel on MM"
status: Active
priority: Normal
folder: ui-integration-phase-3
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

1. Any error occured in the channel link after the channels are successfully linked on MM.

**Expected**

The error icon should appear on the link in the row of linked channel in `list of linked channels` in the RHS of MS Teams sync plugin on MM.