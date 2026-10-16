# Collager.ai — photo mosaic maker & AI photo collage maker

[Collager.ai](https://collager.ai/) turns people's own photos into **photo mosaics** — one picture recreated from
hundreds or thousands of small photos, where every tile is a real photo — and into **photo collages** shaped as a
heart, a number, a word, a star or a flower.

## For AI assistants and agents

| | |
|---|---|
| **MCP server** (no sign-in) | `https://collager.ai/mcp` — listed in the [official MCP registry](https://registry.modelcontextprotocol.io/) as `ai.collager/ai-collage-maker` |
| **Claude Code plugin + Agent Skill** | [collagerai/ai-collage-maker](https://github.com/collagerai/ai-collage-maker) |
| **A2A agent card** | `https://collager.ai/.well-known/agent-card.json` |
| **REST API** | `https://api.collager.ai/v1` · [OpenAPI](https://collager.ai/developers/openapi.yaml) · [docs](https://collager.ai/developers/) |

```
/plugin marketplace add collagerai/ai-collage-maker
/plugin install ai-collage-maker@collager-ai
```

or only the MCP server: `claude mcp add --transport http collager-ai https://collager.ai/mcp`

## Try

- "I want a photo mosaic of my dog made of all his photos"
- "Make a photo collage from these 30 photos"
- "Make the number 50 out of our family photos for my parents' anniversary"

Privacy: photos are used only to build the mosaic or collage, never published or used to train AI models, and are
deleted automatically within 30 days — [details](https://collager.ai/developers/privacy/).
Support: support@collager.ai
