---
name: chatgpt-web-images
description: Generate or edit images through the ChatGPT web chat in the in-app browser when the user requests GPT Images or ChatGPT webpage image generation. Supports arbitrary subjects, supplied reference images, and downloading results.
---

# ChatGPT web image generation

Use the user's ChatGPT web session through the available computer-use browser tools. This is an agent-guided browser workflow, not an API call or an unattended script.

1. Reuse an existing chatgpt.com tab if available; otherwise open https://chatgpt.com/ in the in-app browser. Inspect its state and respect any existing drafts. If necessary create a new chat. Do not require the user to open the page manually.
2. Use the visible Create image/创建图像 control if available. Compose the user's requested subject, format, and constraints. For edits or named subjects, use the actual user-provided reference image(s); ask only if indispensable files cannot be found. Follow browser tool documentation for file uploads and applicable permissions. Never use unrelated personal files as references.
3. Submit the generation request, wait for completion, inspect the visible result, and download the image through the webpage. Put the delivered file in the workspace when possible; link it and the chat. Retain the relevant tab as a deliverable if supported. Check spelling and identity where material.
4. If login, rate limits, missing browser access, or UI changes block the workflow, report the specific blocker and request only the necessary user action. Do not silently switch to API or a different image tool when the webpage was requested. Do not claim a specific backend model version unless the interface or an authoritative source verifies it for that generation.

Keep output topic-neutral: do not assume products, cats, a brand, or a particular aspect ratio. Use the user's stated preferences and files for the current task.
