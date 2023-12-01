---
# (Required) Ensure all values are filled up
name: "Message in prompt interval to connect the account in DM/GM"
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

1. When the `Prompt interval for DMs and GMs` time is set and disconnected user sends a message in DM/GM from MM just after setting the time or after the interval time is completed.

**Expected**

The user should get a message only visible to the disconnected user who send the message regarding to connect their account.