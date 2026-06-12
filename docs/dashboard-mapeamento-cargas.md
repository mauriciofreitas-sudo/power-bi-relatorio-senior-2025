# Dashboard — Mapeamento de Cargas

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Dashboard - Mapeamento_Cargas.pbix |
| Tamanho | 1,85 MB |
| Última modificação | 05/06/2026 |
| Área | Operacional / Logística |

## Objetivo

Mapeamento geográfico e operacional das cargas transportadas pelo Grupo LC Log. Visualiza rotas, volumes por origem/destino e indicadores de entrega. Suporta decisões de roteirização e identificação de oportunidades de consolidação de cargas.

## Fontes de Dados

- Sistema Senior ERP — módulo Transportes / Expedição
- Dados de CT-e emitidos (origem, destino, peso, valor)
- Dados de entrega (data prevista x realizada)
- Tabela de municípios / coordenadas geográficas (para mapa)

## Principais Indicadores

- Volume de cargas por rota (origem → destino)
- Peso total transportado por período
- Valor das cargas por rota
- On-time delivery (% de entregas no prazo)
- Cargas por estado / região
- Mapa de calor de volume por município

## Páginas Esperadas

1. **Mapa** — visualização geográfica das rotas e volumes
2. **Por Rota** — tabela com origem, destino, quantidade e valor
3. **Desempenho** — indicadores de prazo e performance
4. **Histórico** — evolução de volume por período

## Filtros Esperados

- Período
- Estado de origem / destino
- Filial responsável
- Tipo de carga / produto
- Cliente

## Frequência de Atualização

Semanal ou quinzenal.

## Público-Alvo

Gerência Operacional, Coordenação de Logística, Diretoria.

## Observações

- Arquivo leve (1,85 MB) — possivelmente com dados agregados (não granular por nota fiscal).
- Verificar se o mapa usa o visual nativo do Power BI (Bing Maps) ou um visual customizado — o Bing Maps requer conexão com internet.
- Para mapas mais detalhados, considerar integração com Azure Maps ou Mapbox via visual customizado.
- Confirmar se as coordenadas de municípios estão na tabela ou são geradas automaticamente pelo Power BI.
