---
title: "Bug Grouping: sharper AI summaries that refresh as a group grows"
url: "https://docs.luciq.ai/changelog#bug-grouping-sharper-ai-summaries-that-refresh-as-a-group-grows"
date: "2026-08-05"
feed_url: "https://docs.luciq.ai/changelog/rss.xml"
---
What's new? Group AI summaries now reflect the same signals your grouping logic uses: when Bug Grouping considers Network Logs and User Steps, those are factored into the summary alongside the report titles.Summaries regenerate automatically as a group grows — refreshed when the group reaches 3 duplicates, and again at 7 duplicates.Each refresh considers all duplicates in the group, including manually-marked ones, rather than a truncated batch. Why this matters?
