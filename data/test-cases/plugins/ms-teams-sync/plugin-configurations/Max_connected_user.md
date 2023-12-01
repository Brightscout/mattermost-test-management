---
# (Required) Ensure all values are filled up
name: "Maximum connected users"
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

1. When the `Max Connected Users` option is set to some limit and the count of users (connected atleast once) is not equal to the set limit.
2. Connect the new user to MS Teams on MM using the `/msteams-sync connect` command.

**Step 2**

1. When the `Max Connected Users` option is set to some limit and the count of users (connected atleast once) is equal to the set limit.
2. Edit and decrease the limit of `Max Connected Users` option.

**Step 3**

1. When the `Max Connected Users` option is set to some limit and the count of users (connected atleast once) is equal to the set limit.
2. Disconnect one user and connect a new user to MS Teams on MM using the `/msteams-sync connect` command.

**Expected**

The new user should be able to connect to their MS Teams account.
After step 2, the connected users should not get affected.
After step 3, The new user should not be able to connect to their MS Teams account.