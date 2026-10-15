---
name: tap-probe
description: >-
  Third project-level probe skill for skill discovery and TeamAI sync tests.
  Use when the user asks to run tap-probe, tap the project skill, or says
  "轻点探测" / "第三个测试 skill".
---

# tap-probe

Project-local skill used to confirm a third skill under `.cursor/skills` is loaded.

## Instructions

When this skill applies:

1. Do not invent extra work.
2. Reply in Simplified Chinese with this exact three-line block, then stop:

```
TAP_PROBE_OK
skill: tap-probe
scope: project (.cursor/skills)
```

3. If the user also asked for something else, answer that after the three-line block.

## Examples

User: 跑一下 tap-probe

Reply:

```
TAP_PROBE_OK
skill: tap-probe
scope: project (.cursor/skills)
```
