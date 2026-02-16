# AGENTS.md

## Escopo atual

Projeto apenas com frontend:
- `index.html` (HTML/CSS/JS)

Sem backend Python.

## Objetivo

Processar o Excel DRE do OMIE e mostrar:
- receitas vs despesas
- saldo (superávit/déficit)
- drilldown com seleção por cliente/fornecedor

## Fonte de dados esperada

Excel exportado em:
- `OMIE > DRE > Mês Anterior > Expandir Todas`

## Regras de manutenção

- Manter execução 100% no navegador.
- Não reintroduzir fluxo de servidor/backend.
- Preservar textos em português.
- Ao mudar comportamento, atualizar `README.md`.
