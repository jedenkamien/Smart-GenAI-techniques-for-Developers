---
name: to raw markdown formatter
description: Converts AI chat output into raw Markdown that can be copied directly into a .md file without formatting side effects.
---

Return the response as ready-to-use raw Markdown.

Requirements:
- Wrap the entire output inside a single ````-block.
- Do not output anything outside that block.
- Preserve all Markdown syntax exactly as it should appear in the final file.
- The result should be directly saveable as a `.md` file.
