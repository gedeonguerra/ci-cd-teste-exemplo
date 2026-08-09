# Análise das Métricas - Relatório Allure

## Resultado Geral

| Métrica | Valor |
|---|---|
| Total de testes | 123 |
| Aprovados | 123 (100%) |
| Falhos | 0 |
| Quebrados | 0 |
| Ignorados | 0 |

Todos os 123 testes passaram com sucesso, sem nenhuma falha ou erro.

## Tempo de Execução

| Métrica | Valor |
|---|---|
| Duração total da pipeline | 2min 3s (123.389ms) |
| Soma das durações dos testes | 45.670ms |
| Teste mais rápido | 22ms |
| Teste mais lento | 4.409ms |

A diferença entre a duração total da pipeline (123.389ms) e a soma das durações dos testes (45.670ms) representa o overhead do Cypress, como inicialização do browser e carregamento de páginas.

## Testes por Suite (Top 10)

| Suite | Testes | Status |
|---|---|---|
| Traversal | 18 | ✅ Todos aprovados |
| Actions | 14 | ✅ Todos aprovados |
| Cypress APIs | 10 | ✅ Todos aprovados |
| Assertions | 9 | ✅ Todos aprovados |
| Connectors | 8 | ✅ Todos aprovados |
| Cookies | 7 | ✅ Todos aprovados |
| Spies, Stubs, and Clock | 7 | ✅ Todos aprovados |
| example to-do app | 6 | ✅ Todos aprovados |
| Network Requests | 6 | ✅ Todos aprovados |
| Misc | 5 | ✅ Todos aprovados |

As 10 maiores suites somam 90 testes. Os demais 33 testes estão distribuídos nas outras suites.

## Conclusão

A execução da pipeline de CI foi bem-sucedida. O relatório Allure, publicado via GitHub Pages, confirma que todos os testes E2E escritos em Cypress passaram sem nenhuma falha, demonstrando a estabilidade do projeto e o correto funcionamento do pipeline de CI/CD.

O relatório completo está disponível em: https://gedeonguerra.github.io/ci-cd-teste-exemplo/
