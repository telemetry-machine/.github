# Telemetry Machine

[Telemetry Machine](https://telemetrymachine.com) is OpenTelemetry-native observability
for engineers and their coding agents. Send it your traces, logs, metrics and wide
events, then ask it anything about them, yourself or through your agent.

## Connect your coding agent

Telemetry Machine's MCP server is at `https://telemetrymachine.com/api/mcp`. Your agent
signs in with OAuth in the browser, so there's no key to copy.

In Claude Code, install the plugin, which adds the MCP server and our skills:

```text
/plugin install telemetry-machine --marketplace telemetry-machine/agent-skills
```

For Codex, Cursor and other agents, see
[agent-skills](https://github.com/telemetry-machine/agent-skills#install).

Then ask your agent to instrument your app, or to find out why something is slow.

## Links

- [Quick start](https://telemetrymachine.com/docs/quick-start)
- [Documentation](https://telemetrymachine.com/docs), and its
  [index for agents](https://telemetrymachine.com/docs/llms.txt)
- [MCP Registry](https://registry.modelcontextprotocol.io):
  `com.telemetrymachine/telemetry-machine`
- hello@telemetrymachine.com
