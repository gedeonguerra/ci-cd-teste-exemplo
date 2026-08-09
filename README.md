# ci-cd-teste-exemplo

> Projeto de estudo/exercício de curso — mantido como registro de aprendizado.

Projeto simples para aulas de CI-CD, com testes E2E em Cypress executados automaticamente via GitHub Actions a cada push na branch `main`. O pipeline gera relatório Allure e publica no GitHub Pages.

## Stack

- [Cypress](https://www.cypress.io/)
- [Allure Report](https://allurereport.org/)
- GitHub Actions (CI/CD)

## Como rodar

\`\`\`bash
npm install
npm test
npm run report:generate
\`\`\`