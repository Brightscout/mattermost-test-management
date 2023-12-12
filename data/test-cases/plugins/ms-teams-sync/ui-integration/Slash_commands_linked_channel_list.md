---
# (Required) Ensure all values are filled up
name: "Updates in the list of linked channels with slash commands"
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

1. Enter the slash command `/msteams link [msteams-teamID] [msteams-channelID]` in the unlinked channel on MM.
2. Click on MS Teams sync plugin icon in App bar or channel header and open the RHS on MM.

**Step 2**

1. Enter the slash command `/msteams unlink` in the linked channel on MM.
2. Click on MS Teams sync plugin icon in App bar or channel header and open the RHS on MM.

**Step 3**

1. Enter the slash command `/msteams unlink` in all the linked channels on MM
2. Click on MS Teams sync plugin icon in App bar or channel header and open the RHS on MM.

**Expected**

The user should be able to verify the linked channel in the list of linked channels in the RHS of MS Teams sync plugin on MM.
After step 2, The unlinked channel should not be present in the list of linked channels in the RHS of MS Teams sync plugin on MM.
After step 3, The user should be able to see the `Link a channel` button in the RHS of MS Teams sync plugin on MM.