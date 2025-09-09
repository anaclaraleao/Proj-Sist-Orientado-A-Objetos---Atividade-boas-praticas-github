# Repositório Individual - Atividade ASOO Projeto

##  Descrição do Desafio

Uma empresa de médio porte possui um setor de TI responsável por atender solicitações internas de suporte técnico. Atualmente todas as requisições são recebidas por e-mail ou telefone, o que gera dificuldades no controle dos chamados, atrasos e falhas na priorização.
A empresa deseja adotar um sistema integrado, no qual os colaboradores possam registrar suas solicitações e a IA possa sugerir soluções automáticas ou encaminhar ao técnico adequado com base no histórico de chamados e na complexidade do problema.

##  Backlog do Produto

Sprint 1 – Infraestrutura e Base do Sistema
*    Configuração do ambiente de desenvolvimento
*    Configuração do banco de dados SQL Server
*    Definição da arquitetura do sistema (modularidade)
*    Implementação inicial da segurança (criptografia de senhas, autenticação básica)
  
Sprint 2 – Cadastro e Autenticação
*    Desenvolvimento do cadastro de usuários
*    Implementação da autenticação com diferentes níveis de acesso
*    Validação e testes iniciais
  
Sprint 3 – Abertura de Chamados
*    Criar a funcionalidade para abertura de chamados
*    Interface para exibição dos chamados abertos
*    Testes de integração com banco de dados
  
Sprint 4 – Classificação Inteligente (IA)
*    Treinamento inicial da IA com base no histórico de chamados (dados fictícios se necessário)
*    Implementação da sugestão automática de soluções
*    Testes e ajustes no modelo
  
Sprint 5 – Refinamento e Segurança
*    Melhorias na segurança do sistema
*    Ajustes na modularidade e refatoração do código
*    Testes finais e documentação

##  Requisitos do Sistema

### Funcionais

*   **Cadastro de usuário**: Usuários podem se cadastrar no sistema.
*   **Autenticação de login**: Diferentes níveis de acesso.
*   **Abertura de chamados**: Usuários podem registrar requisições de suporte.
*   **Classificação inteligente**: IA analisa chamados e sugere soluções ou encaminha ao técnico adequado.

### Não Funcionais

*   **Banco de dados**: SQL Server.
*   **Segurança**: Implementação de medidas de segurança.
*   **Modularidade**: Design modular do sistema.

## Tabela das Sprints (Referência do Projeto Original)

O projeto original foi dividido em sprints, com os seguintes objetivos e entregas:

| Sprint | Período | Objetivos | Entregas |
| :--- | :--- | :--- | :--- |
| **Sprint 1** | 03/06 - 09/06/2024 | Infraestrutura e base do sistema | Ambiente, DB, segurança inicial |
| **Sprint 2** | 10/06 - 16/06/2024 | Cadastro e autenticação | Cadastro + login |
| **Sprint 3** | 17/06 - 23/06/2024 | Abertura de chamados | CRUD de chamados |
| **Sprint 4** | 24/06 - 30/06/2024 | Classificação inteligente | IA treinada + sugestões |
| **Sprint 5** | 01/07 - 07/07/2024 | Refinamento e testes | Sistema ajustado + documentação |

##  Tecnologias Utilizadas (Referência do Projeto Original)

*   **SQL Server** – banco de dados
*   **(Definir linguagens/frameworks usados, ex: C#, .NET, Java, Node.js, etc.)**
*   **Ferramentas de versionamento**: Git/GitHub

## Estrutura do Projeto

### 🔹 Caso de Uso

<img width="1378" height="2224" alt="431613165-2fa7933b-9304-485c-93a4-ed86c0ff05a8" src="https://github.com/user-attachments/assets/e2f915fd-0cb6-44f0-b03a-b6098592db69" />

Fluxo:

1.  Funcionário faz login → abre chamado
2.  IA recebe e valida chamado
3.  IA define prioridade (alta, média, baixa)
4.  IA resolve ou encaminha ao técnico
5.  Chamado encerrado

### 🔹 Diagrama de Classes

<img width="884" height="1105" alt="diagrama de Classe" src="https://github.com/user-attachments/assets/49d27576-90a7-4d58-968a-a55226579239" />

Representa a estrutura do sistema, com suporte da IA para triagem, histórico e priorização dos chamados.

### 🔹 Diagrama de Sequência

![diagrama de sequencia](https://github.com/user-attachments/assets/64b873dd-35a0-40b3-b705-fc4133ba1311)

### 🔹 Diagrama de Implantação

![diagrama de implantação](https://github.com/user-attachments/assets/d4edfdf2-2116-47cb-a344-0fd5c04b718e)

Representa a arquitetura do sistema de chamados com IA.

## ▶️ Como Executar o Projeto 

```shell
# Clonar repositório
git clone https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto

# Entrar na pasta do projeto
cd Atividade-da-disciplina-ASOO-projeto

# (Rodar comandos de instalação conforme a tecnologia escolhida)
```

##  Equipe

*   **PO**: Ana Clara Leão Ferreira
*   **Scrum Master**: Igor Sene Idalgo
*   **Devs**: Mauricio R. Verdussen, Pedro Henrique T. de Carvalho, Henry M. Damasceno Santos, Vinícius Gobis Novo

