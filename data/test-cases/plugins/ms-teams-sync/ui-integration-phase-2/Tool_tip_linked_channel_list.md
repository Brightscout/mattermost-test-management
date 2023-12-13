---
# (Required) Ensure all values are filled up
name: "Tool tip upon hovering over the name of linked channel"
status: Active
priority: Normal
folder: ui-integration-phase-2
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

1. Hover over the channel name in the `list of linked channels` in the RHS of MS Teams sync plugin on MM.

**Expected**

The user should be able to see the full name of the channel in the tool tip in the RHS of MS Teams sync plugin on MM.