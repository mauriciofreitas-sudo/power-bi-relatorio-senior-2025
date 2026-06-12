# Dashboard — Contas a Pagar

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard - Contas a Pagar.pbix |
| Tamanho | 36,92 MB |
| Última modificação | 12/06/2026 |
| Área | Financeiro / Contas a Pagar |

## Objetivo

Painel de gestão das contas a pagar do Grupo LC Log. Controla vencimentos, fornecedores, status de pagamentos e posição de caixa comprometida. Essencial para o planejamento de fluxo de caixa e negociação com fornecedores.

## Fontes de Dados

- Sistema Senior ERP — módulo Financeiro / Contas a Pagar
- Cadastro de fornecedores Senior
- Natureza de despesa / centro de custo

## Principais Indicadores

- Total a pagar no período (em aberto)
- Aging list: a vencer / vencido (por faixa: 0–30, 31–60, 61–90, >90 dias)
- Contas pagas no mês
- Top fornecedores por valor
- Distribuição por natureza de despesa
- Evolução mensal do saldo a pagar
- Títulos em atraso (valor e quantidade)

## Páginas Esperadas

1. **Visão Geral** — posição atual de contas a pagar
2. **Aging** — títulos por faixa de vencimento
3. **Por Fornecedor** — concentração de pagamentos
4. **Por Natureza** — despesas por categoria
5. **Histórico de Pagamentos** — fluxo realizado

## Filtros Esperados

- Período (data de vencimento / emissão / pagamento)
- Status (em aberto, pago, vencido, cancelado)
- Fornecedor
- Filial / centro de custo
- Natureza de despesa / conta contábil
- Forma de pagamento (boleto, transferência, cheque)

## Frequência de Atualização

Diária (para gestão operacional de fluxo de caixa).

## Público-Alvo

Equipe de Contas a Pagar, Gerência Financeira, Controladoria, Diretoria.

## Observações

- Arquivo médio (36 MB) — atualização razoavelmente rápida.
- Verificar se inclui apenas a empresa sede ou todas as filiais do Grupo LC Log.
- Atentar para o tratamento de títulos compensados parcialmente (abatimentos).
- Considerar adicionar alerta visual para títulos vencidos há mais de 30 dias se ainda não existir.
