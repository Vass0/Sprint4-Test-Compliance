# BetAware – Sprint 4: Plano de Testes (Validação de Sistema)
**Data:** 2025-10-20

Este documento cobre os **testes manuais** exigidos na **PARTE A** do enunciado. Todos os testes usam **dados controlados** (arquivos e valores na pasta `data/`).

## Tabela-resumo (Testes planejados)
| ID   | Título                                      | PBI Relacionado                      | Prioridade |
|------|---------------------------------------------|--------------------------------------|------------|
| TC-01| Importação válida de histórico (CSV)        | PBI 1 – Importar histórico           | Alta       |
| TC-02| Importação inválida (schema incorreto)      | PBI 2 – Normalização                 | Alta       |
| TC-03| Normalização elimina duplicatas             | PBI 2 – Normalização                 | Alta       |
| TC-04| Cálculo de métricas comportamentais         | PBI 3 – Métricas                     | Alta       |
| TC-05| Classificação de risco (alto)               | PBI 4 – Motor de Risco               | Alta       |
| TC-06| Alerta in-app ao logar (risco alto)         | PBI 6 – Alertas                      | Média      |
| TC-07| Relatório e exportação CSV                  | PBI 8 – Relatórios                   | Média      |
| TC-08| Login inválido (negativo)                   | (Login/Segurança)                    | Média      |

## Casos de teste (dados de entrada/saída e passos)
(Conteúdo detalhado conforme alinhado no chat; copie cada caso para o Azure Boards e vincule ao PBI correspondente.)
