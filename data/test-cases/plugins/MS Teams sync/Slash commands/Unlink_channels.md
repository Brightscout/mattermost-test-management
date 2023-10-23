---
# (Required) Ensure all values are filled up
name: "Unlink channel command"
status: Active
priority: Normal
folder: Slash commands
authors: "@AayushChaudhary0001"
team_ownership: 
- Change Team Name
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

1. Run the "/msteams unlink" command in the MM channel which is already linked.

**Step 2**

1. Run the "/msteams unlink" command in the MM channel which is not already linked.

**Expected**

The user should be able to unlink the already linked MM channel from the linked Teams channel. On step 2, the user should receive a message that this MM channel is not linked to any MS Teams channel.o