---
# (Required) Ensure all values are filled up
name: "Member access request in the todo list after entering the `/gitlab todo` slash command."
status: Active
priority: Normal
folder: Subscriptions-and-notifications
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

1. Create subscription in any desired channel or DM/Gm on MM to any desired public project in a public group on gitlab.
2. Create a member access request from a different user to the desired public project on gitlab.
3. Navigate to the desired channel or DM/GM on MM and enter the slash command `/gitlab todo`.

**Expected**

The user should get a list of todo and the notification for member access request should follow the format, `member_access_requested : <user> has requested access to <owner/repo>`.