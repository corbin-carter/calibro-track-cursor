# Calibro Track for Cursor

Connects Cursor to [Calibro Track](https://calibrosoftware.com/track/), time tracking, approval and reporting for Jira Cloud. Log the time you spent on an issue from the session you spent it in, time the session, submit your week, approve your team's time and run reports, all without leaving the editor.

## What's included

- **MCP server**: Calibro Track's seventeen tools, served by Atlassian for Forge apps at `https://mcp.atlassian.com/forge/5b77dba0-26e6-4893-800f-2bf9a4ca9614`.
- **Rule** (`calibro-track`): how the agent should use them. It confirms before writing, never invents minutes, and leaves the date to the app.
- **Skill** (`log-this-session`): time the current session on its Jira issue and log it when you finish.

## Before you connect

1. Calibro Track is installed on your Jira Cloud site ([Atlassian Marketplace](https://marketplace.atlassian.com/apps/3456125435); free for up to 10 users).
2. A site admin has turned on **Allow external MCP access** in Atlassian Administration, under **Settings → Connected apps**.

Cursor asks you to sign in to Atlassian the first time a tool is used. Choose the site Calibro Track is installed on.

## Privacy

The tools run as you, under your own Jira permissions, against Calibro Track's data on Atlassian's platform. See the [privacy policy](https://calibrosoftware.com/legal/privacy/). Docs: [Logging time from an agent](https://calibrosoftware.com/track/docs/logging-time-from-an-agent/).
