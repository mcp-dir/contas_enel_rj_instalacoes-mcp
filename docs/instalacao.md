# Instalação detalhada

Enel RJ: Lista de Instalações é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_contas_enel_rj_instalacoes`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_contas_enel_rj_instalacoes` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_contas_enel_rj_instalacoes` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_contas_enel_rj_instalacoes` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.contas_enel_rj_instalacoes` (ou `servers.contas_enel_rj_instalacoes` no VS Code) do config do cliente e reinicie.
