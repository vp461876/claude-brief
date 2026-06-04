---
description: Open/focus the docked iTerm2 pane showing this session's live brief
argument-hint: "[float|refresh]"
allowed-tools: Bash(~/.claude/bin/brief-open.sh:*)
---
This session's running brief (state · what's been tried · gotchas · decisions ·
next) is shown in a docked iTerm2 pane — a side-by-side split, opened or
re-focused just now. Click the dock pane to use its keys: `r` refresh now ·
`a` toggle **auto** (refresh at the end of each turn — the default; turn off for
on-demand only) · `i` toggle **interval** (refresh periodically during a long
turn; only fires on new activity, so idle never spends) · `+`/`-` set the
interval period (30s–1h) · `?` key help · `q` close. The footer shows both
modes. `/brief refresh` does a one-shot refresh from here but re-splits the pane.

!`~/.claude/bin/brief-open.sh $ARGUMENTS`

Acknowledge in ONE short line that the brief dock is up — or, if the command
above reported an error, relay that error. Do NOT reproduce the brief here.
