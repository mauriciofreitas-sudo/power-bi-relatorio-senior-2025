# Reclamações

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Reclamações.pbix |
| Tamanho | 1,35 MB |
| Última modificação | 12/06/2026 |
| Área | Qualidade / Atendimento ao Cliente |

## Objetivo

Gestão e análise das reclamações recebidas de clientes do Grupo LC Log. Permite categorizar, priorizar e acompanhar a resolução das reclamações, medindo o tempo de resposta e a satisfação final do cliente.

## Fontes de Dados

- Sistema de gestão de reclamações (Senior, CRM ou planilha)
- Dados de cliente do Senior ERP
- Registros de ocorrências operacionais (se vinculadas a reclamações)

## Principais Indicadores

- Total de reclamações no período
- Reclamações por status (aberta, em análise, resolvida, encerrada)
- Tempo médio de resposta (TMA)
- Tempo médio de resolução (TMR)
- Reclamações por categoria (atraso, avaria, extravio, cobrança, outros)
- Top clientes com mais reclamações
- Taxa de resolução no prazo (SLA)
- Reclamações por filial / operação

## Páginas Esperadas

1. **Visão Geral** — totais e semáforo de SLA
2. **Por Categoria** — distribuição por tipo de reclamação
3. **Por Cliente** — clientes com maior volume
4. **Tempo de Resposta** — análise de SLA e eficiência
5. **Histórico** — evolução mensal de reclamações

## Filtros Esperados

- Período (data de abertura / encerramento)
- Status
- Categoria / subcategoria
- Cliente
- Filial responsável
- Analista responsável

## Frequência de Atualização

Diária ou semanal.

## Público-Alvo

Supervisão de Qualidade, Atendimento ao Cliente, Gerência Operacional, Diretoria.

## Observações

- Arquivo leve (1,35 MB) — volume de reclamações baixo ou histórico curto.
- Verificar se existe integração com o módulo de ocorrências do Senior para cruzar reclamações com falhas operacionais (atrasos, avarias).
- Avaliar exibição do indicador de **reincidência** — clientes que reclamam do mesmo problema mais de uma vez.
- Confirmar se as categorias de reclamação estão padronizadas para permitir análise temporal consistente.
