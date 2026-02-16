# NoHarm Finance - DRE (HTML + JS)

Aplicação 100% client-side para processar o Excel do OMIE:
- `OMIE > DRE > Mês Anterior > Expandir Todas`

## Como usar

1. Abra `index.html` no navegador.
2. Faça upload do arquivo `.xlsx` do DRE.
3. Ajuste receitas/despesas se necessário.
4. Use os checkboxes no drilldown para incluir/remover itens do cálculo.

## Regras do cálculo

- Agrupa por `Cliente ou Fornecedor`.
- Valores positivos entram como `Receitas`.
- Valores negativos entram como `Despesas` (valor absoluto).
- Resultado final:
  - `Saldo = Receitas - Despesas`
  - saldo positivo => `Superávit`
  - saldo negativo => `Déficit`
