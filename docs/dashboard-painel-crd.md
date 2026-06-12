# Dashboard — Painel CRD

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard - Painel CRD.pbix |
| Tamanho | 98,40 MB |
| Última modificação | 11/06/2026 |
| Área | Operacional / Distribuição |

## Objetivo

Painel de acompanhamento do **CRD (Controle de Romaneio de Distribuição)**. Controla as entregas realizadas pelos veículos, status de romaneios, devoluções e performance da operação de distribuição last-mile ou transferência.

## Fontes de Dados

- Sistema Senior ERP — módulo Expedição / Distribuição
- Romaneios de entrega emitidos
- Registros de entrega, devolução e ocorrência
- CT-e vinculados aos romaneios

## Principais Indicadores

- Total de romaneios emitidos no período
- Romaneios entregues x pendentes x com devolução
- % de efetividade de entrega
- Quantidade de volumes por romaneio
- Ocorrências por tipo (cliente ausente, endereço errado, recusa, outros)
- Custo por entrega (se disponível)
- Produtividade por motorista / veículo

## Páginas Esperadas

1. **Visão Geral** — totais e indicadores de efetividade
2. **Por Motorista / Veículo** — produtividade individual
3. **Ocorrências** — detalhamento por tipo de problema
4. **Devoluções** — análise de cargas não entregues
5. **Histórico** — evolução de volume e performance

## Filtros Esperados

- Período (data de emissão / entrega)
- Filial / base de distribuição
- Status do romaneio
- Motorista / veículo
- Cliente / região de entrega
- Tipo de ocorrência

## Frequência de Atualização

Diária (operação de distribuição requer acompanhamento em tempo real ou D-1).

## Público-Alvo

Supervisor de Distribuição, Gerência Operacional, Coordenação de Logística.

## Observações

- **Arquivo grande (98 MB)** — próximo do limite de 100 MB para certos recursos do Power BI Service.
- Alto volume de dados indica histórico longo carregado ou nível de granularidade por romaneio/volume individual.
- Avaliar filtro de período padrão para limitar dados carregados (ex: últimos 90 dias) e reduzir o tamanho.
- Verificar se há necessidade de modo **DirectQuery** para dados de ontem/hoje (dados quentes) combinado com Import para histórico.
