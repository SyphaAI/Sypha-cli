# Sypha CLI

The AI coding agent built for the terminal. Generate code from natural language, automate tasks, and run terminal commands — powered by 500+ AI models.

Visit [sypha.ai](https://sypha.ai)

## Install

```bash
npm install -g @sypha-ai/cli
```

Or run directly with npx:

```bash
npx @sypha-ai/cli
```

## Getting Started

Run `sypha` in any project directory to launch the interactive TUI:

```bash
sypha
```

Run a one-off task:

```bash
sypha run "add input validation to the login form"
```

## Features

- **Code generation** — describe what you want in natural language
- **Terminal commands** — the agent can run shell commands on your behalf
- **500+ AI models** — use models from OpenAI, Anthropic, Google, and more
- **MCP servers** — extend agent capabilities with the Model Context Protocol
- **Multiple modes** — Plan with Architect, code with Coder, debug with Debugger, or create your own
- **Sessions** — resume previous conversations and export transcripts
- **API keys optional** — bring your own keys or use Sypha credits

## Commands

| Command | Description |
|---------|-------------|
| `sypha` | Launch interactive TUI |
| `sypha run "<task>"` | Run a one-off task |
| `sypha auth` | Manage authentication |
| `sypha models` | List available models |
| `sypha mcp` | Manage MCP servers |
| `sypha upgrade` | Upgrade to the latest version |

Run `sypha --help` for the full list.

## Alternative Installation

**conda:**

```bash
conda install -c sypha_ai sypha-cli
```

## Links

- [Website](https://sypha.ai)
- [GitHub](https://github.com/SyphaAI/Sypha-cli)
- [Issues](https://github.com/SyphaAI/Sypha-cli/issues)

## License

Proprietary software. See [LICENSE](https://github.com/SyphaAI/Sypha-cli/blob/main/LICENSE) for details.
