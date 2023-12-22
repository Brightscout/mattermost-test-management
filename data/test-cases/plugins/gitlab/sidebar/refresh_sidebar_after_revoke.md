---
# (Required) Ensure all values are filled up
name: "Refresh the sidebar after revoking the application from the gitlab."
status: Active
priority: Normal
folder: Sidebar
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

1. Revoke the OAuth token for your app from the connectd gitlab account.
2. Navigate to MM and click on the refresh button in the LHS of gitlab.
3. Open the gitlab bot chat.

**Step 2**

1. Revoke the OAuth token for your app from the connectd gitlab account.
2. Navigate to MM and refresh the page.
3. Open the gitlab bot chat.

**Step 3**

1. Revoke the OAuth token for your app from the connectd gitlab account.
2. Navigate to MM and enter any slash command that fetches the data from the gitlab.
3. Open the gitlab bot chat.

**Expected**

The LHS of gitlab should be removed and the user should get a message that the account has been disconnected in the gitlab bot chat on MM.
After step 2, the LHS of gitlab should be removed and the user should get a message that the account has been disconnected in the gitlab bot chat on MM.
After step 3, the LHS of gitlab should be removed and the user should get a message that the account has been disconnected in the gitlab bot chat on MM.
