# Dashboard — Performance Geral

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard - Performance Geral.pbix |
| Tamanho | 277,60 MB |
| Última modificação | 26/04/2026 |
| Área | Estratégico / Multi-área |

## Objetivo

Relatório estratégico consolidado de performance geral do Grupo LC Log. O maior arquivo do diretório (277 MB), reúne KPIs de múltiplas áreas — financeiro, operacional, frota, comercial e atendimento — em uma visão integrada para a alta gestão.

## Fontes de Dados

- Sistema Senior ERP — múltiplos módulos
  - Financeiro (faturamento, inadimplência, custos)
  - Transportes (CT-e, romaneios, entregas)
  - Frota (custo, utilização, km)
  - RH (headcount, se aplicável)
- Possível integração com outras bases externas

## Principais Indicadores

### Financeiro
- Receita bruta / líquida de frete
- EBITDA / margem operacional (se disponível)
- Inadimplência
- Custos fixos e variáveis

### Operacional
- Volume de cargas transportadas (ton, m³, ou volumes)
- On-time delivery (OTD)
- Ocorrências e devoluções

### Frota
- Frota ativa e disponível
- Custo por km rodado (CPKm)
- Km total rodado

### Comercial
- Faturamento por cliente / segmento
- Novos clientes no período
- Receita por rota / região

## Páginas Esperadas

1. **Executive Summary** — KPIs estratégicos com semáforos
2. **Financeiro** — receita, custos e margens
3. **Operacional** — volume e performance de entrega
4. **Frota** — utilização e custo
5. **Comercial** — faturamento por cliente
6. **Histórico** — evolução dos principais indicadores

## Filtros Esperados

- Período (mês/ano)
- Filial / regional
- Segmento de cliente
- Centro de custo

## Frequência de Atualização

Mensal (relatório estratégico de fechamento).

## Público-Alvo

Diretoria, Conselho, Alta Gestão do Grupo LC Log.

## Observações

- **Arquivo muito grande (277 MB)** — o maior do diretório. Pode ser lento para abrir no Power BI Desktop e ao publicar no Service.
- **Atenção:** última modificação em 26/04/2026 — verificar se dados estão atualizados ou se há atualização agendada no Service.
- Considerar as seguintes otimizações:
  - Reduzir o período histórico carregado (últimos 24 meses em vez de histórico completo)
  - Usar **agregações** para tabelas de fato volumosas
  - Avaliar **Composite Model** (Import + DirectQuery) para dados recentes
- Ao publicar no Service, pode ser necessário workspace Premium ou PPU pelo tamanho do dataset.
- Este relatório provavelmente é o mais crítico da coleção — priorizar qualidade e consistência dos dados.
