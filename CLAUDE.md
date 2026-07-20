# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Workspace Overview

This is a personal agent workspace (Agente P) used for running Claude Code sessions. It has no application codebase of its own — work here typically involves scripting, automation, skill installation, or managing external projects.

## Configured Permissions

The `.claude/settings.local.json` pre-approves the following tool calls without prompting:

- `Bash(gh api *)` — GitHub API calls via the `gh` CLI
- `WebFetch(domain:raw.githubusercontent.com)` — fetching raw GitHub file content
- `WebFetch(domain:api.github.com)` — GitHub REST API requests
