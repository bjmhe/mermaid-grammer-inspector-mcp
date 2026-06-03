# <img src="https://mermaid.js.org/favicon.svg" height="24"/> Mermaid Grammer Inspector

[![Mermaid-Grammer-Inspector MCP server](https://glama.ai/mcp/servers/bjmhe/Mermaid-Grammer-Inspector/badges/score.svg)](https://glama.ai/mcp/servers/bjmhe/Mermaid-Grammer-Inspector)
[![npm version](https://npmx.dev/api/registry/badge/version/@bjmhe/mermaid-grammer-inspector-mcp)](https://npmjs.com/package/@bjmhe/mermaid-grammer-inspector-mcp)
[![npm downloads](https://npmx.dev/api/registry/badge/downloads/@bjmhe/mermaid-grammer-inspector-mcp)](https://npm.chart.dev/@bjmhe/mermaid-grammer-inspector-mcp)
[![bundle size](https://npmx.dev/api/registry/badge/size/@bjmhe/mermaid-grammer-inspector-mcp)](https://bundlephobia.com/package/@bjmhe/mermaid-grammer-inspector-mcp)
[![license](https://npmx.dev/api/registry/badge/license/@bjmhe/mermaid-grammer-inspector-mcp)](https://github.com/betterhyq/mermaid_grammer_inspector_mcp/blob/main/LICENSE)

A Model Context Protocol (MCP) server for validating Mermaid diagram syntax and providing comprehensive grammar checking capabilities

## Usage

Install the package:

<!-- automd:pm-install global auto=false -->

```sh
# npm
npm installg @bjmhe/mermaid-grammer-inspector-mcp

# yarn
yarn addg @bjmhe/mermaid-grammer-inspector-mcp

# pnpm
pnpm addg @bjmhe/mermaid-grammer-inspector-mcp

# bun
bun installg @bjmhe/mermaid-grammer-inspector-mcp

# deno
deno installg npm:@bjmhe/mermaid-grammer-inspector-mcp

# vp
vp installg @bjmhe/mermaid-grammer-inspector-mcp
```

<!-- /automd -->

### NPX Cursor Config

```json
{
  "mcpServers": {
    "mermaid-grammer-inspector": {
      "command": "npx",
      "type": "stdio",
      "transportType": "stdio",
      "args": ["-y", "mermaid-grammer-inspector"]
    }
  }
}
```

### Http Cursor Config

start the service locally

```bash
mermaid-grammer-inspector --http --port=4000
```

set the config

```json
{
  "mcpServers": {
    "mermaid-grammer-inspector": {
      "url": "http://0.0.0.0:4000/sse",
      "type": "sse",
      "transportType": "sse"
    }
  }
}
```

## License

<!-- automd:contributors license=MIT -->

Published under the [MIT](https://github.com/bjmhe/mermaid-grammer-inspector-mcp/blob/main/LICENSE) license.
Made by [community](https://github.com/bjmhe/mermaid-grammer-inspector-mcp/graphs/contributors) 💛
<br><br>
<a href="https://github.com/bjmhe/mermaid-grammer-inspector-mcp/graphs/contributors">
<img src="https://contrib.rocks/image?repo=bjmhe/mermaid-grammer-inspector-mcp" />
</a>

<!-- /automd -->

<!-- automd:with-automd -->

---

_🤖 auto updated with [automd](https://automd.unjs.io)_

<!-- /automd -->
