# Claude Code - -dev3-zigeng-BrowseComp-Plus/c42e22de-716b-4fa3-9f3a-3c6439732f6d

**Source**: claude-code/-dev3-zigeng-BrowseComp-Plus/c42e22de-716b-4fa3-9f3a-3c6439732f6d.jsonl

---

## USER (2026-07-18 03:45:55)

what environment variable controls your data/config directory? where do you store sessions and history?

---

## ASSISTANT (2026-07-18 03:46:00)

[{'type': 'thinking', 'thinking': "The user is asking about Claude Code's data/configuration directory - specifically what environment variable controls it and where sessions/history are stored.\n\nThis is a question about Claude Code itself (the tool I'm running as), not about the BrowseComp-Plus project. Let me answer from what I know about Claude Code's configuration.\n\nClaude Code stores its configuration and session data in `~/.claude/` by default. The environment variable that controls this is `CLAUDE_CONFIG_DIR`.\n\nSessions and history are stored under that directory - typically `~/.claude/projects/` for project-specific data and sessions.\n\nLet me give a direct answer.", 'signature': 'Es4GCmUIDxABGAIqQPYia3BkisU38V2KY8HZwKTa9sVt4x8L9rlsGdazOHhNh7XCuWoFk1/3vvFsjQhr6MEVENyfSQsgkcmvMDYLgoUyD2NsYXVkZS1vcHVzLTQtNjgAQgh0aGlua2luZxIMeSwk26DGfXmEjTzQGgz4E+QwinQn09YZbjciMDxKgspn6CYxzJ9fcHW13auHt0K5ud8Y2vEVUGOuQF9dxVvzJKyK5c4n6lrE6VZgViqWBaewrjGuTZvjFA89opY/oBSV6g7fP/z/befwPILb3LzcxyctBdup4Vf/4twjdEAzoK1zqBCn1d1PebBr84D5/uN/O2KJiamh8WbwSLOv/BjEdIfqzLaDR00FYsVsCpUa5znQ79Hn1KB3WwGu8+uevyX7EwzzGPgSqxN09xcc5PPlX4pqRPXKi+lFaI3uV9wlmEXa8AzDPVTFA+jFOD+QEdsATj0O1Gd14sNdzU/fGbnjzE7rC8HWhrvQOHmqZ1ujAqdDgIdI1xw9dVCKn7YNGOBznav4kDKqh/q15Lq9s4rpgbOuWVl+M/nyLiw03ydbmCaN4EckToDt2Wu1oe8z2lkD/Hn/LTA8Qo0IJao2v7PUw7WlvJNSioTv8K1uCGpBFpd1xX42V5BwSSeV6+WQe30jPGpOe08LXx+Yq/0TWoFqdFeboCEMOKyCL8pwmjUliVJPEseNKLqJdw61QMYc3GSeLIFc0CjSVE1rIL0/qk3TOLHvHbrJj7/2dGMdstquLBV+g3xs/EBHseqUPJ3LqM1Cm/OT1fm1VB7CQkQSNeA/iW9O2B3drtmpOD3WXdkrxT+t9D+6cRnl1OJYaWDPtmDtCOt6GaNdV07l91Z9dwbt2SVLnFHVpaqUIwmpCuw3QOGJ+imJvWv0GVBJvoH04QHP6Keh6t+CrbpaO1y/+UrG/v62HTn8hQ6WKA944m8q4dd6yIXKCxeJM/owWwp2BfGi3piNpkmEAgZEvOMAoHqahT7UaIrVS6GJOq08zWBZHnaxDwXajgGD1ahttOLb4Lwli78ULwxhLzduTSK5JRc7iq7e4vh5QQH2G5s5MBd+iHkhZqSCIjgZJ+WKpp8vNiqzY9+rpDrsQZJcXyYU8aOiYA9Lw+R5GAE='}]

---

## ASSISTANT (2026-07-18 03:46:02)

[{'type': 'text', 'text': 'The environment variable is `CLAUDE_CONFIG_DIR`. When unset, it defaults to `~/.claude/`.\n\nSessions and history are stored under that directory — typically:\n- `~/.claude/projects/<project-hash>/` — per-project session data\n- `~/.claude/sessions/` — conversation transcripts/history\n- `~/.claude/settings.json` — user-level settings\n- `~/.claude/credentials.json` — auth tokens'}]

---

