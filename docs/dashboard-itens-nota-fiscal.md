# Dashboard — Itens Nota Fiscal

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard_ItensNotaFiscal.pbix |
| Tamanho | 121,34 MB |
| Última modificação | 12/06/2026 |
| Área | Fiscal / Compras / Estoque |

## Objetivo

Análise detalhada dos **itens de notas fiscais** de entrada e/ou saída. Permite rastrear produtos/serviços adquiridos, fornecedores, tributos incidentes e conformidade fiscal. O nível de granularidade por item explica o tamanho expressivo do arquivo (121 MB).

## Fontes de Dados

- Sistema Senior ERP — módulo Fiscal / NF-e
- XML das notas fiscais eletrônicas (NF-e)
- Cadastro de produtos / serviços Senior
- Cadastro de fornecedores / clientes Senior
- Tabela de NCM / CFOP / CST

## Principais Indicadores

- Total de notas fiscais no período (quantidade e valor)
- Valor total por fornecedor / emitente
- Distribuição por NCM (classificação fiscal do produto)
- Tributos: ICMS, IPI, PIS, COFINS, ISS por item
- Top produtos / serviços adquiridos
- Notas por CFOP e natureza de operação
- Valor médio por nota / por item

## Páginas Esperadas

1. **Resumo de NF** — totais de notas e valores
2. **Por Fornecedor** — concentração de compras
3. **Por Produto / NCM** — análise de itens
4. **Tributos** — ICMS, PIS, COFINS e outros
5. **Detalhes** — listagem granular de itens
6. **Histórico** — evolução mensal

## Filtros Esperados

- Período (data de emissão / entrada)
- Tipo de nota (entrada, saída)
- Fornecedor / emitente
- Produto / descrição
- NCM
- CFOP
- Filial / CNPJ destinatário
- Status (autorizada, cancelada)

## Frequência de Atualização

Diária ou semanal, conforme volume de notas fiscais.

## Público-Alvo

Equipe Fiscal, Controladoria, Compras, Auditoria Interna.

## Observações

- **Arquivo muito grande (121 MB)** — resultado do nível de detalhe por item de NF, que pode gerar milhões de linhas.
- Estratégias recomendadas para reduzir o tamanho:
  - Limitar o histórico carregado (ex: últimos 12 meses) e criar relatório de histórico separado
  - Usar **incremental refresh** no Power BI Service para carregar apenas notas novas
  - Avaliar **agregações** para análises de alto nível e manter detalhe apenas para drill-through
- Confirmar se o relatório cobre NF-e de entrada, saída ou ambas — separar em relatórios específicos se necessário.
- Verificar se notas canceladas estão sendo excluídas corretamente para não distorcer os valores.
