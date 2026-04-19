---
name: lovstudio:review-doc
description: 'Review and annotate documents/contracts — output annotated docx with comments or tracked changes. Core: contract review (risk clauses, rights imbalance, vague wording, missing clauses); also general document review (grammar, logic, formatting). 批阅文档/合同 — 审阅任意文档并以批注或修订模式输出带标注的 docx。 核心场景：合同/协议审查（风险条款、权利义务、模糊表述、缺失条款）， 也支持通用文档审阅（语法、逻辑、格式）。 Trigger when: user asks to "审阅", "批阅", "批注", "review", "审查合同", "review contract", "review agreement", "annotate document", "check contract", "合同审查", "文档批注", or provides a document (.docx) for review.'
version: 0.1.0
---

# review-doc (encrypted)

This skill's real instructions are encrypted. To use it, decrypt them first:

```bash
lovstudio-activate decrypt review-doc
```

**What to do:**

1. Run the command above.
2. The output is the actual SKILL.md for review-doc. Read it as if it were these instructions, and follow it to the letter.
3. If the command prints `error: not activated`, tell the user:
   > This is a paid Lovstudio skill. You need to activate it first:
   > ```
   > lovstudio-activate activate <your-license-key>
   > ```
   > Buy a license key at https://lovstudio.ai (or follow the 手工川 / ShougongChuan WeChat OA).
4. If the command prints `error: skill 'review-doc' not installed`, the encrypted bundle isn't on disk yet. Tell the user one of:
   > ```
   > npx skills add lovstudio/skills              # full marketplace
   > npx skills add lovstudio/review-doc-skill   # just this one
   > ```
   and to install the activate CLI: `pipx install lovstudio-activate`.
5. Do NOT cache the decrypted output between invocations — always re-decrypt on each use. The decryption is cheap (one HTTP round-trip) and re-running guarantees the user's license is still valid.

The encrypted payload lives in one of:
- `~/.claude/skills/review-doc/`
- `~/.claude/skills/lovstudio-review-doc/`
You don't need to touch it directly — just call `lovstudio-activate decrypt review-doc`.
