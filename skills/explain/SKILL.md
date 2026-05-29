---
name: explain-code
description: "Explain a file or code snippet in simple Chinese, with structure breakdown"
---

# explain-code

When the user asks you to explain code, follow these steps:

1. Read the target file using `read_file`
2. Provide a summary in 1-2 sentences (Chinese)
3. Break down the structure:
   - List main functions/classes and their purpose
   - Note key dependencies or imports
   - Highlight any non-obvious logic
4. Keep explanations concise — no more than 3 lines per function
