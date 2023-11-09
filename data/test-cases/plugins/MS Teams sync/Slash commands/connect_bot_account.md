---
# (Required) Ensure all values are filled up
name: "Connect-bot slash command"
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

1. Run the "/msteams-sync connect-bot" command.
2. Click on the link provided.
3. Enter the valid credentials.

**Expected**

The user should be able to connect the bot account to the desired Teams account.