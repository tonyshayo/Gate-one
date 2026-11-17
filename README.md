# Gate-one

Contém as skills do [Travel Hacking Toolkit](https://github.com/borski/travel-hacking-toolkit) (licença MIT, commit `d10f6ca`) como *project skills* do Claude Code, para uso em sessões na nuvem onde `/plugin` não está disponível.

- `.claude/skills/` — 42 skills (ex.: `/getting-started`, `/seats-aero`, `/plan-trip`)
- `.claude/agents/travel-hacker.md` — subagente
- `data/` — dados de parceiros de transferência, valuations, sweet spots etc.
- `CLAUDE.md` — instruções do toolkit

Os servidores MCP do toolkit (`.mcp.json`) não foram incluídos; a busca de milhas usa o conector seats.aero da conta.
