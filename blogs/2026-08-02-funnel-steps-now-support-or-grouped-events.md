---
title: "Funnel steps now support OR-grouped events"
url: "https://docs.luciq.ai/changelog#funnel-steps-now-support-or-grouped-events"
date: "2026-08-02"
feed_url: "https://docs.luciq.ai/changelog/rss.xml"
---
What's new? The apm_funnel_write MCP tool takes an ordered steps array, and each step is an OR group of up to 5 events. A session completes the step as soon as any of that step's events occurs.
