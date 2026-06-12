# Crédito Conta Contábil

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Crédito Conta Contábil.pbix |
| Tamanho | 180,58 MB |
| Última modificação | 12/06/2026 |
| Área | Financeiro / Contabilidade |

## Objetivo

Análise dos créditos lançados por conta contábil no sistema Senior. Permite rastrear a origem dos créditos, identificar contas com maior volume e auditar lançamentos contábeis do período.

## Fontes de Dados

- Sistema Senior ERP — módulo Contabilidade (tabelas de lançamentos contábeis)
- Plano de Contas do Grupo LC Log
- Centro de Custo / Filial

## Principais Indicadores

- Total de créditos por conta contábil
- Valor médio de lançamento por conta
- Distribuição por filial / centro de custo
- Evolução mensal dos créditos por conta
- Top contas contábeis por volume de crédito
- Comparativo Realizado x Orçado (se disponível)

## Páginas Esperadas

1. **Resumo** — total de créditos consolidados
2. **Por Conta** — drill-down por conta contábil
3. **Por Filial / Centro de Custo** — distribuição geográfica
4. **Histórico** — evolução por período
5. **Detalhes** — listagem dos lançamentos individuais

## Filtros Esperados

- Período (data de competência / data de lançamento)
- Conta contábil (código / descrição)
- Filial
- Centro de custo
- Natureza do lançamento

## Frequência de Atualização

Mensal, após fechamento contábil.

## Público-Alvo

Controladoria, Contabilidade, Diretoria Financeira.

## Observações

- **Arquivo grande (180 MB)** — indica alto volume de lançamentos importados em modo Import. Pode ser lento para abrir e atualizar.
- Avaliar uso de **DirectQuery** ou **agregações** para reduzir o tamanho caso o volume continue crescendo.
- Ao publicar no Power BI Service, verificar se o tamanho está dentro do limite do workspace (padrão: 1 GB por dataset).
- Garantir que o gateway de dados está configurado apontando para o banco do Senior antes de agendar atualização automática.
