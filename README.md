# ORACLE Higher Self Generator

A provenance-aware skills-only plugin for guided Higher Self Codex interviews, symbolic memetic charts, and separate user-centered avatar imagery.

## Included

- Portable root manifest: `plugin.json`
- Codex compatibility manifest: `.codex-plugin/plugin.json`
- Oracle workflow skill: `skills/oracle-codex/SKILL.md`

The skill distinguishes user-reported material, externally generated charts, calculated data, verified sources, interpretive synthesis, and unknown fields. Traditional Maya Tzolk'in and José Argüelles' Dreamspell are treated as separate systems. Human Design is currently supplied by a user-generated external chart screenshot or pasted result.

## Sharing and installation

Giving someone this repository link lets ChatGPT inspect the source, but does not automatically install the plugin into their account.

For local testing with Codex CLI and the ChatGPT desktop app, add the repository as a marketplace:

```powershell
codex plugin marketplace add https://github.com/ArcaneParadigm/Higher-Self-Generator.git --ref main
codex plugin list
codex plugin add oracle-codex@higher-self-generator
```

Then restart the ChatGPT desktop app, open the Plugins Directory, select **Higher Self Generator**, and install **ORACLE Higher Self Generator**. Start a new chat and ask it to create a Higher Self Codex. The repository also includes `.agents/plugins/marketplace.json`, which is the catalog used by this installation flow.

If the repository remains private, the recipient must have GitHub access and an authenticated Git client. A public repository is required for unauthenticated sharing.

For broad public installation, submit the plugin through OpenAI's plugin submission portal. After review and publication, users install it from the shared Plugins Directory.

This repository currently contains a skills-only plugin. No MCP server, authentication service, database, or hosted endpoint is included.
