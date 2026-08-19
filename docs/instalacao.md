# Instalação detalhada

SEFAZ SP: Cupom Fiscal Eletrônico (SAT) - Detalhado é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_sp_cfe_completa`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_sp_cfe_completa` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_sp_cfe_completa` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_sp_cfe_completa` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_sp_cfe_completa` (ou `servers.sefaz_sp_cfe_completa` no VS Code) do config do cliente e reinicie.
