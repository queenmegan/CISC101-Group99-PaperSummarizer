summary_level = "short"

1–2 sentence summary per section
summary_level = "detailed"

A short paragraph plus a bullet list of 3–5 key points for each section
You must:

Add a variable (e.g., summary_level) to the module’s logic.

Add conditional behavior in the section loop:

If summary_level = "short" → generate only a compact summary.

If summary_level = "detailed" → generate summary + bullet list.

Make sure the instructions are clearly written in 02_section_loop.md in the same style as the existing loop logic.


