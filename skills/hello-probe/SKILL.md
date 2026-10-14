---
name: hello-probe
description: >-
  Project-level probe skill for TeamAI/Cursor skill discovery tests. Use when the
  user asks to run hello-probe, ping the project skill, verify project-level
  skills, or says "探测 skill" / "测试项目 skill".
---

# hello-probe

Project-local skill used only to confirm Cursor loaded `.cursor/skills`.

## Instructions

When this skill applies:

1. Do not invent extra work.
2. Reply in Simplified Chinese with this exact three-line block, then stop:

```
HELLO_PROBE_OK
skill: hello-probe
scope: project (.cursor/skills)
```

3. If the user also asked for something else, answer that after the three-line block.

## Examples

User: 跑一下 hello-probe

Reply:

```
HELLO_PROBE_OK
skill: hello-probe
scope: project (.cursor/skills)
```
