# Como enviar um MCP

1. Confirme que o servidor é público e que você é o mantenedor, ou tem autorização de quem mantém.
2. Adicione uma entrada em `marketplace.json`, em `entries`, seguindo `schema/marketplace.schema.json`.
3. Use uma versão fixa no `install.args` (por exemplo `exa-mcp-server@1.2.3`). Não use `latest`.
4. Liste em `env` as variáveis que o servidor precisa. Nunca coloque valores de chave no arquivo.
5. Abra um pull request. A equipe revisa o código do servidor antes de aprovar.

Entradas começam como `"trust": "community"`. Só a equipe da PlifResearch muda para `"verified"`, depois de revisão.
