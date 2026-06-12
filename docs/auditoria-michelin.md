# Auditoria Michelin

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Auditoria_Michelin.pbix |
| Tamanho | 1,58 MB |
| Última modificação | 11/06/2026 |
| Área | Auditoria / Pneus / Frota |

## Objetivo

Relatório de auditoria do contrato de pneus com a Michelin. Acompanha a conformidade do fornecimento, consumo, durabilidade e custo por pneu aplicado na frota do Grupo LC Log.

## Fontes de Dados

- Sistema Senior ERP — módulo de Manutenção / Almoxarifado
- Planilha ou API de controle de pneus Michelin (se integrado)
- Registros de trocas e reformas de pneus

## Principais Indicadores

- Quantidade de pneus consumidos por período
- Custo total e custo por pneu
- Km médio por pneu (durabilidade)
- Conformidade com o contrato (SLA Michelin)
- Pneus em garantia / reclamações abertas
- Distribuição por veículo / eixo / frota

## Filtros Esperados

- Período (mês/ano)
- Filial / garagem
- Tipo de pneu / medida
- Veículo / placa

## Frequência de Atualização

Mensal, alinhada ao ciclo de auditoria do contrato Michelin.

## Público-Alvo

Gerência de Manutenção, Controladoria, Auditor do contrato Michelin.

## Observações

- Arquivo leve (1,58 MB) — poucos dados históricos carregados ou alta filtragem na fonte.
- Existe uma versão específica para TV CGR (`Auditoria_Michelin - TV CGR.pbix`) com layout adaptado para painel público.
- Verificar periodicidade de envio dos dados pelo fornecedor Michelin.
