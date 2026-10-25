# agent-plugins

My Claude Code plugin market

# How to Use

## Add marketplace

Claude:

```shell
claude plugin marketplace add https://github.com/xchacha20-poly1305/agent-plugins.git
```

Codex:

```shell
codex plugin marketplace add https://github.com/xchacha20-poly1305/agent-plugins.git
```

## Install plugin

Claude:

```shell
claude plugin install <plugin-name>@anrong-plugins
```

Codex:

```shell
codex plugin add <plugin-name>@anrong-plugins
```

# Plugins

## pet4agents

<https://github.com/xchacha20-poly1305/pet4agents>

Use Codex pet in agent tools that support Claude plugin.

## grok-agent

<https://github.com/xchacha20-poly1305/grok-agent>

Use Grok as a cheap and fast agent.

## peon-py

<https://github.com/xchacha20-poly1305/peon-py>

Another [openpeon](https://openpeon.com/) implementation for Claude Code / Codex plugin.

## material-icon-download

<https://github.com/xchacha20-poly1305/agent-plugins>

Download icons from [fonts.google.com](https://fonts.google.com).

## bline

<https://github.com/xchacha20-poly1305/bline>

Show the model, its reasoning effort and the context window usage on the line under the Claude Code prompt. Claude Code only.

## ccpii

<https://github.com/xchacha20-poly1305/ccpii>

Replace personal data in prompts and tool results with numbered placeholders before the model reads them, using [openai/privacy-filter](https://huggingface.co/openai/privacy-filter) locally; tool calls get the real values back. Claude Code only.
