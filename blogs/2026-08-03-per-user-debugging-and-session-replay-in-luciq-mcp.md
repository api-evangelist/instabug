---
title: "Per-user debugging and session replay in Luciq MCP"
url: "https://docs.luciq.ai/changelog#per-user-debugging-and-session-replay-in-luciq-mcp"
date: "2026-08-03"
feed_url: "https://docs.luciq.ai/changelog/rss.xml"
---
What's new? Two new Luciq MCP tools: user_summary and list_session_replays.user_summary returns one end user's devices, OS and app versions, sessions, per-metric APM occurrences by Apdex class, and the crashes and bugs they hit, all in a single call.list_session_replays lists recorded sessions for an app, newest first, with a dashboard deep link on every row. It's also the only MCP tool that can look a user up by email.Several existing tools (list_crashes, list_app_hangs, list_bugs, list_occurrences_tokens, apm_list_groups, apm_group_view, apm_occurrence) can now filter by specific user IDs.
