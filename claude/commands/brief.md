---
description: Open/focus the docked iTerm2 pane showing this session's live brief
argument-hint: "[float|refresh]"
allowed-tools: Bash(~/.claude/bin/brief-open.sh:*)
---
This session's running brief (state · what's been tried · gotchas · decisions ·
next) is shown in a docked iTerm2 pane — a side-by-side split, opened or
re-focused just now. It refreshes itself after every completed turn; during a
long turn, click the dock pane and press `r` to refresh on demand, or `a` to
toggle auto-refresh (every 5m, but only while there's new activity, so an idle
session doesn't spend); `q` closes the dock. `/brief refresh` does the same
one-shot refresh from here but re-splits the pane.

!`~/.claude/bin/brief-open.sh $ARGUMENTS`

Acknowledge in ONE short line that the brief dock is up — or, if the command
above reported an error, relay that error. Do NOT reproduce the brief here.
