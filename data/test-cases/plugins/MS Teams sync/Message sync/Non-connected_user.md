---
# (Required) Ensure all values are filled up
name: "Message from non-connected user"
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

1. Enter the desired text message in the already linked MM channel by the account which is not already connected.

**Step 2**

1. Connect the bot-account.
2. Enter the desired text message in the already linked MM channel by the account which is not already connected.

**Expected**

The message should not be reflected on the linked Teams channel. After step 2, the message provided should be reflected by the bot account contaning the original user's name in the message in the linked channel in Teams.
