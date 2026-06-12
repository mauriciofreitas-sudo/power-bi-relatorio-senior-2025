# DashBoard — Painel CTE

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | DashBoard - Painel CTE.pbix |
| Tamanho | 27,94 MB |
| Última modificação | 09/06/2026 |
| Área | Fiscal / Transportes |

## Objetivo

Painel de acompanhamento dos **Conhecimentos de Transporte Eletrônico (CT-e)** emitidos pelo Grupo LC Log. Controla a situação fiscal dos documentos de transporte, valores, tomadores, remetentes e status junto à SEFAZ.

## Fontes de Dados

- Sistema Senior ERP — módulo Fiscal / Transportes
- XML dos CT-e emitidos (via Senior ou integração com SEFAZ)
- Tabela de destinatários / tomadores
- CFOP e natureza de operação

## Principais Indicadores

- Quantidade de CT-e emitidos no período
- Valor total dos fretes faturados
- CT-e por status: autorizado, cancelado, denegado, em processamento
- Distribuição por CFOP / tipo de operação
- Faturamento por tomador / remetente
- Evolução mensal do faturamento de frete
- Ticket médio por CT-e
- CT-e por filial emissora

## Páginas Esperadas

1. **Visão Geral** — totais de emissão e valor
2. **Status Fiscal** — situação junto à SEFAZ
3. **Por Tomador** — faturamento por cliente/tomador
4. **Por Filial** — emissão por filial/CNPJ emitente
5. **Histórico** — evolução mensal de emissões e valores
6. **Cancelamentos** — análise de CT-e cancelados

## Filtros Esperados

- Período (data de emissão)
- Status (autorizado, cancelado, denegado)
- Filial / CNPJ emitente
- Tomador do serviço
- UF de início / fim da prestação
- CFOP

## Frequência de Atualização

Diária.

## Público-Alvo

Equipe Fiscal, Faturamento, Gerência Financeira, Controladoria.

## Observações

- Arquivo de tamanho médio (27 MB) — dados bem controlados para volume de CT-e de uma transportadora.
- Verificar se os CT-e de terceiros (subcontratação) também estão incluídos ou apenas os próprios.
- Confirmar tratamento de CT-e complementares e de substituição (não duplicar valores).
- Para conformidade fiscal, garantir que CT-e denegados e cancelados sejam tratados separadamente no modelo.
