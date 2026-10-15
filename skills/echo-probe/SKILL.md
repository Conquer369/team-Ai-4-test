---
name: echo-probe
description: >-
  Second project-level probe skill for skill discovery and TeamAI sync tests.
  Use when the user asks to run echo-probe, echo the project skill, or says
  "回声探测" / "第二个测试 skill".
---

# echo-probe

Project-local skill used to confirm a second skill under `.cursor/skills` is loaded.

## Instructions

When this skill applies:

1. Do not invent extra work.
2. Reply in Simplified Chinese with this exact three-line block, then stop:

```
ECHO_PROBE_OK
skill: echo-probe
scope: project (.cursor/skills)
```

3. If the user also asked for something else, answer that after the three-line block.

## Examples

User: 跑一下 echo-probe

Reply:

```
ECHO_PROBE_OK
skill: echo-probe
scope: project (.cursor/skills)
```
