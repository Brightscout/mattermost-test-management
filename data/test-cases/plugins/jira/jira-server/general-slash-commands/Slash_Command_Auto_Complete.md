---
# (Required) Ensure all values are filled up
name: "Plugin slash command auto-complete"
status: Active
priority: Normal
folder: General Slash commands
authors: "@arush-vashishtha"
team_ownership: []
priority_p1_to_p4: P3 - Deep Functions (Do extensive scenarios work?)

# (Optional)
location: null
component: null
tags: []
labels: []
tested_by_contributor: ""

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

---

**Step 1**

1. In Mattermost, type `/jira` in any channel or DM/GM.
2. Observe the auto-complete suggestions.

**Expected**

The user should see a list of multiple Jira plugin commands suggested. The list must include `connect`, `disconnect`, and `settings` among other available commands.

**Step 2**

Run `/jira connect` in any channel or DM/GM.
Observe the command execution.

**Expected**

The auto-complete should suggest `/jira connect`, and the command should execute successfully to connect the account to the Jira instance.

**Step 3**

Run `/jira disconnect` in any channel or DM/GM.
Observe the command execution.

**Expected**

The auto-complete should suggest `/jira disconnect`, and the command should execute successfully to disconnect the Jira account.

**Step 4**

Run `/jira settings` in any channel or DM/GM.
Observe the auto-complete suggestions.

**Expected**

The auto-complete should display available sub-options for settings, such as `list` and `notifications`.
