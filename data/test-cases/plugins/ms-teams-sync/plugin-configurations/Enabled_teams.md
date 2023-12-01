---
# (Required) Ensure all values are filled up
name: "Enabled teams on MM"
status: Active
priority: Normal
folder: plugin-configurations
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

1. Leave the `enabled teams` option empty and send message in any linked channel on MM or MS Teams.
2. Navigate to the linked channel in MS Teams or MM respectively.

**Step 2**

1. Add the team name in `enabled teams` option and send the message in any linked channel of the added team on MM or MS Teams.
2. Navigate to the linked channel in MS Teams or MM respectively.

**Expected**

The message should get synced in the linked channel on MS Teams or MM respectively.
After step 2, the message should not get synced in the linked cchannel on MS Teams or MM respectively.