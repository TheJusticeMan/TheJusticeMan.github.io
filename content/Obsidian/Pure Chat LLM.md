---
title: Pure Chat LLM
---
> Agentic AI plugin for Obsidian. Turns your vault into a dynamic workspace with tools for search, editing, voice chats, and more. Multi-provider: OpenAI, Gemini, xAI.

## Features
- **Agentic Tools**: 13+ functions (e.g., `search_vault`, `create_obsidian_note`, `suno_music_gen`).
- **Voice Calls**: Real-time WebRTC with OpenAI Realtime API.
- **Safety**: Modal approvals for all actions.
- **Multi-Provider**: GPT-4o, Grok, local models.
- **UI Control**: Manage tabs, workspaces, notifications.

### Tools Table
| Tool                  | Description                          |
|-----------------------|--------------------------------------|
| `generate_image`     | AI image from prompts.              |
| `create_obsidian_note` | New notes with frontmatter.        |
| `search_vault`       | Boolean/regex searches.             |
| `suno_music_gen`     | AI music/lyrics via Suno.           |
| `manage_workspace`   | Tabs, splits, views.                |
| *(Full list in GitHub)* |                                      |

v2.0: 131KB bundle, full JSDoc.

## Installation
1. Obsidian: Settings > Community Plugins > Install "Pure Chat LLM".
2. Add API keys in settings.
3. Open chat: Cmd/Ctrl + P > "Pure Chat".

## Examples
- "Search 'GUI standards' and outline improvements." → Uses `search_vault` + writes note.
- "Generate EDM track: Alan Walker style, 128 BPM." → Calls `suno_music_gen`.
- "Summarize [[Personal Background]]." → Reads and responds.

## Setup & Customize
- Settings: API keys, max tokens, memory.
- Dev: Extend via `/src/tools/`.

## Troubleshooting
- API errors: Verify keys.
- Voice: Check mic permissions.
- Issues: [GitHub](https://github.com/TheJusticeMan/pure-chat-llm/issues).

## License
MIT. Contribute: PRs welcome.

[GitHub](https://github.com/TheJusticeMan/pure-chat-llm)

[![Pure Chat LLM Banner](https://img.shields.io/badge/Obsidian-Plugin-8B5CF6?style=for-the-badge&logo=obsidian&logoColor=white)](https://github.com/TheJusticeMan/pure-chat-llm)

![https://img.shields.io/badge/any_text-you_like-blue](https://img.shields.io/badge/any_text-you_like-blue)