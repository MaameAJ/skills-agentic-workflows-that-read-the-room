# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Recent updates (August 2026)

### GitHub Copilot: new models and agent plugins

**Agent Plugins 1.0 is now available** in VS Code, the Copilot CLI, and the Copilot app. Build a plugin once and use it across all compatible agent clients. ([GitHub Changelog, Aug 12](https://github.blog/changelog/2026-08-12-agent-plugins-1-0-in-vs-code-copilot-cli-and-the-copilot-app))

Two new models joined GitHub Copilot this week:
- **Grok 4.6** (xAI) — a reasoning model designed for agentic coding tasks. ([GitHub Changelog, Aug 14](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot))
- **Gemini 3.7 Flash** (Google) — a fast, lightweight model rolling out across Copilot. ([GitHub Changelog, Aug 13](https://github.blog/changelog/2026-08-13-gemini-3-7-flash-is-now-available-in-github-copilot))

### Working with agents

**Canvases make agent work visible and steerable.** The GitHub Blog explains how to use canvases with agentic workflows so the full context of an agent session stays reviewable — and cost-efficient. ([GitHub Blog, Aug 17](https://github.blog/ai-and-ml/github-copilot/how-canvases-make-agentic-workflows-visible-steerable-and-cost-efficient/))

**Four GitHub Agent Apps now cover the full SDLC.** Scope, secure, roll out, and ship features without leaving GitHub. ([GitHub Blog, Aug 14](https://github.blog/ai-and-ml/github-copilot/how-to-bring-your-software-delivery-workflow-into-github-with-agent-apps/))

### Platform improvements

- **Block users from comments** in personal repositories — you can now block or unblock someone directly from a PR or issue comment. ([GitHub Changelog, Aug 13](https://github.blog/changelog/2026-08-13-block-users-from-comments-in-personal-repositories))
- **Rule insights dashboard** is in public preview at the organization level — a visual view of how repository rules apply across your org. ([GitHub Changelog, Aug 12](https://github.blog/changelog/2026-08-12-rule-insights-for-organizations-in-public-preview))
- **License data quality improvements** — GitHub now cross-references package registries (npm, PyPI) to improve dependency license detection. ([GitHub Changelog, Aug 13](https://github.blog/changelog/2026-08-13-license-data-quality-improvements))
- **OAuth app improvements** — multiple redirect URIs and token refresh are now supported for more secure app development. ([GitHub Changelog, Aug 14](https://github.blog/changelog/2026-08-14-multiple-redirect-uris-and-token-refresh-for-oauth-apps))

### Awesome Copilot: community agents and plugins

The [Awesome Copilot](https://awesome-copilot.github.com) site lists 221+ community agents, instructions, skills, and plugins. Install any plugin in one command:

```bash
copilot plugin install <plugin-name>@awesome-copilot
```

The site also has a [Learning Hub](https://awesome-copilot.github.com/learning-hub) with guides covering agents, skills, hooks, MCP servers, and agentic workflows. ([Awesome Copilot](https://awesome-copilot.github.com))
