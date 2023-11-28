---
# (Required) Ensure all values are filled up
name: "Reactions from a disconnected account"
status: Active
priority: Normal
folder: reactions-to-message
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

1. When the account is disconnected and the bot account is connected, add reaction to the bot message in the linked channel on MS Teams.
2. Navigate to the linked channel on MM.

**Step 2**

1. When the account is disconnected, add reaction to a user message in the linked channel on MS Teams.
2. Navigate to the linked channel on MM.

**Step 3**

1. When the account is disconnected and the bot account is connected, add reaction on a message in the linked channel on MM.
2. Navigate to the linked channel on MS Teams.

**Expected**

The reaction should not get added to the message in the linked channel on MM.
After step 2, the reaction should get added to the message in the linked channel on MM.
After step 3, the reaction should not get added to the message in the linked channel on MS Teams.