# Definition of Done (DoD)

**O que é o Definition of Done (DoD)?**
Em Engenharia de Software e metodologias ágeis (como Scrum), o Definition of Done (Definição de Pronto) é um acordo explícito e compartilhado por toda a equipe sobre o conjunto de critérios que uma tarefa, funcionalidade ou User Story deve obrigatoriamente atender para ser considerada 100% finalizada. 

Seu objetivo é garantir a transparência e a qualidade, evitando o famoso "tá pronto, só falta testar" ou "na minha máquina funciona". O DoD assegura que o incremento de software esteja realmente em condições de ser entregue e utilizado pelo cliente.

---

### Checklist Prática: 5 Itens do Definition of Done (DoD)

Para que uma tarefa seja movida para a coluna "Done" (Pronto), a equipe deve verificar se:

- [ ] **1. Desenvolvimento e Code Review Concluídos:** O código foi escrito seguindo as boas práticas e padrões da equipe, e foi revisado e aprovado por pelo menos um outro desenvolvedor (Pull Request aprovado).
- [ ] **2. Testes Automatizados Criados e Passando:** Foram escritos testes (unitários, de integração ou e2e) para a nova funcionalidade, e a esteira de CI/CD rodou todos os testes do projeto com sucesso (build verde).
- [ ] **3. Critérios de Aceite Atendidos e Validados (QA):** A funcionalidade foi testada em um ambiente de homologação (staging) e cumpre exatamente todos os requisitos funcionais e não funcionais que foram definidos no início da tarefa.
- [ ] **4. Documentação Atualizada:** Qualquer alteração necessária na documentação foi feita (ex: rotas novas no Swagger/Postman atualizadas, README modificado, notas de versão ou manuais do usuário ajustados).
- [ ] **5. Código Mergeado na Branch Principal:** O código foi integrado à branch principal (`main` ou `master`) de forma limpa, sem conflitos, e não quebrou nenhuma funcionalidade existente no sistema.
