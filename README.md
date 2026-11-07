# ChatGPT Web Images for Codex

A reusable Codex skill for creating and editing images through ChatGPT's web interface using an available computer-use browser. It guides Codex to reuse a ChatGPT tab, submit a prompt, attach requested references, inspect the result, and download it.

## Requirements

- Codex with a supported computer-use browser and access to this skill.
- A signed-in ChatGPT account with image generation available.
- For image edits, the reference images and permission to upload them.

This is an agent-guided browser workflow. It is not an image model, an OpenAI API client, or an unattended background service. Availability and interface details depend on ChatGPT and the browser environment. No particular model version is guaranteed.

## Install

Clone or download this repository as chatgpt-web-images inside your Codex skills directory, typically ~/.codex/skills/, then restart Codex if needed for discovery. Review SKILL.md before installing any skill.

## Usage

Ask Codex: “Use ChatGPT web image generation to create …” or invoke $chatgpt-web-images and provide your prompt and any reference images. The skill works with arbitrary subjects.

## Privacy

Reference files submitted to ChatGPT are uploaded to the service. Check the destination and your account's applicable data settings before sharing sensitive images. The skill does not include credentials, personal reference photos, or a user's conversation history.

## License

MIT. This independent community project is not affiliated with or endorsed by OpenAI.
