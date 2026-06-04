---
description: Open/focus the docked iTerm2 pane showing this session's live brief
argument-hint: "[float|refresh]"
allowed-tools: Bash(~/.claude/bin/brief-open.sh:*)
---
This session's running brief (state · what's been tried · gotchas · decisions ·
next) is shown in a docked iTerm2 pane — a side-by-side split, opened or
re-focused just now. It refreshes itself after every completed turn. Click the
dock pane to use its keys: `r` refresh now · `a` toggle auto-refresh (only fires
when there's new activity, so an idle session never spends) · `+`/`-` change the
auto interval (30s–1h) · `p` toggle the per-turn refresh so the brief updates
**on demand only** (a `⏸` shows in the footer) · `?` key help · `q` close.
`/brief refresh` does a one-shot refresh from here but re-splits the pane.

!`~/.claude/bin/brief-open.sh $ARGUMENTS`

Acknowledge in ONE short line that the brief dock is up — or, if the command
above reported an error, relay that error. Do NOT reproduce the brief here.
