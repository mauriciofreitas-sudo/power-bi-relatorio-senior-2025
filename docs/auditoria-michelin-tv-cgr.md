# Auditoria Michelin — TV CGR

## Identificação

| Campo | Valor |
|---|---|
| Arquivo | Auditoria_Michelin - TV CGR.pbix |
| Tamanho | 1,34 MB |
| Última modificação | 29/05/2026 |
| Área | Auditoria / Pneus / Frota |

## Objetivo

Versão do relatório de Auditoria Michelin formatada para exibição em **TV/monitor da Central de Gestão Regional (CGR)**. Apresenta os mesmos indicadores do relatório principal (`Auditoria_Michelin.pbix`), mas com layout otimizado para leitura à distância — fontes maiores, menos filtros interativos, foco nos KPIs principais.

## Fontes de Dados

- Mesmas fontes do relatório `Auditoria_Michelin.pbix`
- Sistema Senior ERP — módulo de Manutenção / Almoxarifado

## Principais Indicadores (exibição em TV)

- Km médio por pneu (destaque visual)
- Custo total de pneus no mês
- Quantidade de pneus trocados
- Semáforo de conformidade do contrato (verde/amarelo/vermelho)

## Configuração de Exibição

- Modo de publicação recomendado: **Power BI Service → Publicar na Web** ou configurar em loop automático via Power BI Report Server
- Resolução alvo: 1920x1080 (Full HD)
- Rotação automática: configurar no navegador ou via Power BI mobile

## Frequência de Atualização

Sincronizada com `Auditoria_Michelin.pbix` — mensal.

## Público-Alvo

Equipe operacional da CGR, supervisores de frota no local.

## Observações

- **Não renomear este arquivo** — o sufixo `TV CGR` identifica a finalidade e diferencia da versão analítica.
- Arquivo menor que a versão analítica (1,34 MB vs. 1,58 MB) — confirmando que é uma visão simplificada.
- Ao atualizar indicadores no relatório principal, replicar as mudanças nesta versão TV.
