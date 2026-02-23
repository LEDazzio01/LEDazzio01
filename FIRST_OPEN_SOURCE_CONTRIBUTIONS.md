# 🎉 First Open Source Contributions! 🎉

**Date:** February 23, 2026  
**Repository:** [microsoft/agent-framework](https://github.com/microsoft/agent-framework)  
**Contributor:** [@LEDazzio01](https://github.com/LEDazzio01)

---

## Pull Requests Submitted

### 1. 📝 PR [#4198](https://github.com/microsoft/agent-framework/pull/4198) — Declarative Workflow YAML Schema Documentation
- **Issue:** [#4188](https://github.com/microsoft/agent-framework/issues/4188)
- **Type:** Documentation
- **Summary:** Created comprehensive documentation for the Declarative Workflow YAML schema, covering structure, triggers, actions, expressions, variables, and examples.

### 2. 🔧 PR [#4199](https://github.com/microsoft/agent-framework/pull/4199) — .NET JSON Parsing Fix
- **Issue:** [#4195](https://github.com/microsoft/agent-framework/issues/4195)
- **Type:** Bug Fix (.NET)
- **Summary:** Fixed JSON arrays of objects being incorrectly parsed as empty records when no schema is defined, by adding a `HasSchema` check in `DetermineElementType()`.

### 3. 🐛 PR [#4200](https://github.com/microsoft/agent-framework/pull/4200) — Python AG-UI Streaming Fix
- **Issue:** [#4194](https://github.com/microsoft/agent-framework/issues/4194)
- **Type:** Bug Fix (Python)
- **Summary:** Fixed doubled `tool_call` arguments in `MESSAGES_SNAPSHOT` events during client-side tool streaming. Added duplicate detection guard in `_emit_tool_call()` with full test coverage.
- **Bonus:** Responded to Copilot code review feedback, moved duplicate check for consistency with `_emit_text()`, and added regression test.

## Additional Contribution

### 🔍 Issue [#4187](https://github.com/microsoft/agent-framework/issues/4187) — Root Cause Analysis
- **Type:** Documentation Bug Analysis
- **Summary:** Identified that the Python pivot of the "Multi-Selection Edges" docs page incorrectly displayed C# headings. Located the source file in `MicrosoftDocs/semantic-kernel-docs` and posted a detailed root cause analysis with the exact fix.

---

## Milestones Achieved ✅

- [x] Found and claimed open issues
- [x] Wrote clean, well-documented code fixes
- [x] Opened well-structured pull requests
- [x] Responded to automated code review feedback
- [x] Signed the Microsoft Contributor License Agreement (CLA)
- [x] Contributed across **3 languages** — Python, C#/.NET, and Markdown

---

> *"Every expert was once a beginner."*  
> — First of many contributions! 🚀
