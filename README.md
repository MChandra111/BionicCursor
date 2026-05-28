# Bionic Cursor

Cursor plugin that implements **Bionic Reading** for Agent Chat by instructing the agent to format its prose with bolded word prefixes.

## What it does

- Formats assistant prose like: `**Bion**ic **Read**ing **impr**oves **scan**ning`
- Avoids bolding inside code blocks / inline code, and skips styling for code-heavy messages

## Install (local)

1. Copy (or symlink) this folder into your local plugins directory:
   - Windows: `%USERPROFILE%\.cursor\plugins\local\bionic-cursor\`
2. Reload Cursor.

## Enable / disable

- The rule `rules/bionic-reading.mdc` is set to `alwaysApply: true`.
- To disable it, change `alwaysApply` to `false` (or remove the file from the plugin).

## Submitted to marketplace, should be public soon ^^
