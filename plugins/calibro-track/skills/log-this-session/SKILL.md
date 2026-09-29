---
name: log-this-session
description: Time the current coding session in Calibro Track and log it to the Jira issue being worked on. Use when the user starts work on a Jira issue and wants it timed, or asks to log the time spent in this session.
---

# Log this session

## When to use

- The user starts work on a Jira issue and says to track it, time it, or "start the clock".
- The user finishes and asks to log, record or book the time spent on the session.

## Instructions

1. **Find the issue.** Use the key the user gives, the branch name if it contains one, or Find issues for a description. Confirm the key if it was not stated outright.
2. **At the start, use the timer.** Check Timer status first. If a timer is already running on another issue, say which, and ask whether to switch before calling Start timer with switchFromRunning. Put a short note on what the session is for in the description.
3. **At the end, stop the timer.** Call Stop timer. Only send a description if the user gave a new one; otherwise the note from the start is kept. A timer under a minute is paused, not saved: ask whether to keep it (saveAnyway) or discard it.
4. **If no timer was running,** ask how long the session took. Do not work it out from the conversation. Then confirm the issue and minutes, and call Log time with no work date.
5. **Report the entry** that was written, with its ID and minutes, and remind the user that it is a draft until they submit it.
