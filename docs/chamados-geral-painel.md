# ChamadosGeral Painel

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | ChamadosGeral Painel (1).pbix |
| Tamanho | 2,11 MB |
| Última modificação | 12/06/2026 |
| Área | Suporte / TI / Atendimento Interno |

## Objetivo

Painel completo de gestão de chamados internos. Versão mais abrangente que `chamados.pbix`, com visões consolidadas por equipe, SLA e categoria. Permite gestão do backlog e acompanhamento de performance do time de suporte.

## Fontes de Dados

- Sistema de chamados interno (GLPI, Senior ou equivalente)
- Dados de colaboradores / setores do Senior RH (para cruzar solicitante)

## Principais Indicadores

- Total de chamados no período (abertos / encerrados / pendentes)
- SLA: % de atendimentos dentro do prazo
- Tempo médio de primeira resposta
- Tempo médio de resolução por categoria
- Chamados por setor solicitante (mapa de calor)
- Ranking de categorias mais recorrentes
- Tendência mensal de volume de chamados

## Páginas Esperadas

1. **Visão Geral** — totais e semáforos de SLA
2. **Por Categoria** — detalhamento por tipo de chamado
3. **Por Equipe** — distribuição entre analistas
4. **Histórico** — evolução mensal

## Filtros Esperados

- Período (data de abertura / encerramento)
- Status
- Categoria / subcategoria
- Equipe / analista responsável
- Setor solicitante
- Prioridade

## Frequência de Atualização

Diária.

## Público-Alvo

Coordenador / Gerente de TI, Diretoria (SLA overview).

## Observações

- O `(1)` no nome do arquivo provavelmente indica que foi baixado como cópia — verificar se há versão mais recente no servidor ou Power BI Service.
- Renomear para `ChamadosGeral Painel.pbix` assim que confirmada a versão definitiva.
- Arquivo maior que `chamados.pbix` — confirma que é a versão mais completa e atual.
