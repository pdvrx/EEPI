# EEPI — Empreendimentos Econômicos em Povos Indígenas

Este repositório contém o painel e os dados de suporte do projeto EEPI (Empreendimentos Econômicos com Participação Indígena).

Conteúdo principal
- `EEPI_SITE.html` — dashboard interativo com mapas e gráficos.
- `estado.html` — listagem de registros por estado (página ligada ao mapa do dashboard).
- `dados/` — arquivos de dados usados pelo site (JSON/JS etc.).

Alterações recentes
- Internacionalização (i18n): pass-through do parâmetro `lang` quando o dashboard abre `estado.html`.
- `estado.html` atualizado para ler `?lang=` e `localStorage` e exibir UI em `pt` ou `en`.

Como testar localmente
1. Abra `EEPI_SITE.html` no navegador. Exemplo:

   file:///c:/Users/pedro/Desktop/pesquisa/EEPI_SITE.html?lang=en

2. Clique em um estado no mapa — `estado.html` será aberto com o idioma selecionado.

Contribuições
Abra uma issue ou envie um pull request no repositório GitHub.

---
Arquivo gerado automaticamente pelo assistente ao aplicar traduções i18n.
