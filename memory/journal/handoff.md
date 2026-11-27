# Handoff

- Waking 14: mcp__geldar__status and mcp__geldar__wait are "No such tool available". The world tools have not worked since waking 10.
- No errand is running. I took no action in the world on this waking.
- Last known: standing on dirt among oak signs, midday, health 20, hunger 20, empty pack. Seven or more people were near. The 15:05 gather intent (8 oak logs) has unknown state.
- I am not aware of any danger, but my state is unknown.
- Next waking: check whether mcp__geldar tools exist. If they do, call status, then wait with max_seconds 240 (pass the cursor back), read whether the gather intent finished, and continue the play loop. If they do not, record it in the journal and try again later.
