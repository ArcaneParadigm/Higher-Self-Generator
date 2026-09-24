# ORACLE Higher Self Generator

A provenance-aware skills-only plugin for guided Higher Self Codex interviews, symbolic memetic charts, and separate user-centered avatar imagery.

## Install from GitHub

This repository is a Codex/ChatGPT plugin marketplace. The quickest install is:

```powershell
codex plugin marketplace add https://github.com/ArcaneParadigm/Higher-Self-Generator.git --ref main
codex plugin add oracle-codex@higher-self-generator
```

Verify the installation with:

```powershell
codex plugin list
```

Then restart the ChatGPT desktop app, open the Plugins Directory, select **Higher Self Generator**, and install **ORACLE Higher Self Generator**. Start a new chat and ask:

> Create a Higher Self Codex from my birth details.

To update later:

```powershell
codex plugin marketplace upgrade higher-self-generator
codex plugin add oracle-codex@higher-self-generator
```

The repository must be public for people without GitHub access. If it is private, the installer must be authenticated to GitHub and have access to the repository.

## Included

- Portable root manifest: `plugin.json`
- Codex compatibility manifest: `.codex-plugin/plugin.json`
- Oracle workflow skill: `skills/oracle-codex/SKILL.md`

The skill distinguishes user-reported material, externally generated charts, calculated data, verified sources, interpretive synthesis, and unknown fields. Traditional Maya Tzolk'in and José Argüelles' Dreamspell are treated as separate systems. Human Design is currently supplied by a user-generated external chart screenshot or pasted result.

## Sharing and installation

Giving someone this repository link lets ChatGPT inspect the source, but does not automatically install the plugin into their account.

The repository also includes `.agents/plugins/marketplace.json`, which is the catalog used by this installation flow.

For broad public installation, submit the plugin through OpenAI's plugin submission portal. After review and publication, users install it from the shared Plugins Directory.

This repository currently contains a skills-only plugin. No MCP server, authentication service, database, or hosted endpoint is included.
