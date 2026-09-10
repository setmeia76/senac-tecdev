# Documento de Pesquisa e Levantamento de Requisitos

## 1. Visão Geral
- **Projeto:** [Nome do Projeto]
- **Data:** [Data]
- **Responsável:** [Nome do Analista/PO ou equipe]

## 2. Perfis de Usuários (Personas)
- **Perfil 1 (ex: Cliente do App):** [Descrição breve do que este usuário busca e quais suas necessidades]
- **Perfil 2 (ex: Lojista/Restaurante):** [Descrição dos objetivos e como usará o sistema]
- **Perfil 3 (ex: Administrador):** [Descrição dos privilégios de controle e gestão]

## 3. Requisitos Funcionais (O QUE o sistema fará)
*(Lembre-se: Ações práticas, fluxos e interações que o usuário pode executar)*

| ID | Nome do Requisito | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF01** | Cadastro de Usuário | O sistema deve permitir que o cliente crie uma conta usando e-mail ou conta Google. | Alta |
| **RF02** | [Nome da Funcionalidade] | [O sistema deve permitir...] | [Alta/Média/Baixa] |
| **RF03** | [Nome da Funcionalidade] | [O sistema deve permitir...] | [Alta/Média/Baixa] |

## 4. Requisitos Não Funcionais (COMO o sistema deve se comportar)
*(Lembre-se: Desempenho, segurança, escalabilidade, usabilidade e restrições)*

| ID | Categoria | Descrição |
| :--- | :--- | :--- |
| **RNF01** | **Desempenho** | O tempo de carregamento da página inicial não deve ultrapassar 2 segundos. |
| **RNF02** | **Segurança** | As senhas devem ser armazenadas com criptografia forte (ex: bcrypt) e o tráfego deve usar HTTPS. |
| **RNF03** | **[Categoria]** | [Descrição da restrição de qualidade ou infraestrutura] |

## 5. Regras de Negócio
*(Restrições e condições lógicas que o software precisa respeitar de acordo com as leis do negócio)*
- **RN01:** Um pedido só pode ser cancelado se o status ainda for "Aguardando Confirmação".
- **RN02:** [Descreva uma regra restritiva, ex: cálculo de frete, idade mínima, regras de desconto, etc.]

## 6. Glossário
*(Termos específicos do negócio para que toda a equipe técnica entenda o vocabulário)*
- **Termo 1:** [Significado no contexto do projeto]

## 7. Dúvidas e Pendências (Parking Lot)
*(Use este espaço durante as reuniões para anotar coisas que precisam de investigação)*
- [ ] Como o sistema legado vai enviar os dados de estoque?
- [ ] Precisamos contratar um gateway de pagamento ou usaremos o atual?
