# Dashboard — Custos Frota

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard - Custos_Frota.pbix |
| Tamanho | 12,15 MB |
| Última modificação | 29/04/2026 |
| Área | Frota / Custos Operacionais |

## Objetivo

Detalhamento e análise dos custos da frota do Grupo LC Log. Cobre todas as categorias de despesa relacionadas aos veículos: combustível, manutenção, pneus, pedágios, IPVA, seguro e outras. Permite identificar veículos com alto custo e oportunidades de redução.

## Fontes de Dados

- Sistema Senior ERP — módulo Frota / Manutenção
- Almoxarifado (consumo de peças e pneus)
- Abastecimento (combustível por veículo)
- Integração com sistema de pedágio (se disponível)

## Principais Indicadores

- Custo total da frota no período
- Custo por veículo / placa
- Custo por km rodado (CPKm)
- Distribuição por categoria de custo (combustível, manutenção, pneu, pedágio, outros)
- Evolução mensal de custos
- Top 10 veículos mais caros
- Comparativo custo real x orçado

## Páginas Esperadas

1. **Visão Geral** — custo total e distribuição por categoria
2. **Por Veículo** — ranking e detalhes por placa
3. **Combustível** — consumo e custo de abastecimento
4. **Manutenção** — ordens de serviço e peças
5. **Histórico** — evolução de custos por período

## Filtros Esperados

- Período (mês/ano)
- Filial / garagem
- Categoria de custo
- Tipo de veículo (truck, carreta, van, utilitário)
- Placa / veículo
- Motorista

## Frequência de Atualização

Mensal, após consolidação dos lançamentos de frota.

## Público-Alvo

Gerência de Frota, Controladoria, Diretoria Operacional.

## Observações

- Arquivo de tamanho médio-baixo (12 MB) — carga de dados bem controlada.
- **Atenção:** última modificação em 29/04/2026 — verificar se o relatório está desatualizado ou se a atualização de dados é automática via Service.
- Cruzar com o relatório `AGREGADO X FROTA.pbix` para comparar custo entre frota própria e agregados.
- Verificar se o custo de pneus está duplicado entre este relatório e os relatórios de Auditoria Michelin.
