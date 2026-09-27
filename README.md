# Nova marketplace

Claude Code marketplace for [Nova](https://github.com/voidcraft-labs/nova-plugin) — build, edit, compile, and deploy CommCare apps from Claude Code.

## Install

    /plugin marketplace add voidcraft-labs/nova-marketplace
    /plugin install nova@nova-marketplace

See the [Nova docs](https://docs.commcare.app/claude-code) for the full guide.

The marketplace points to the plugin repository. Agent definitions and MCP
configuration belong to the plugin so an update has one source of truth.

## Update

Refresh the marketplace and plugin, then restart Claude Code:

    /plugin marketplace update nova-marketplace
    /plugin update nova

Version 2 uses OAuth by default. See the [plugin authentication guide](https://github.com/voidcraft-labs/nova-plugin#authenticate) for optional API-key setup.
