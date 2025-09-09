# Repositório Individual - Atividade ASOO Projeto

## 📝 Descrição do Projeto

Este repositório individual foi criado como parte da atividade da disciplina de Análise e Projeto Orientado a Objetos (ASOO), com o objetivo de aplicar as boas práticas de uso do Git e GitHub, conforme o guia fornecido. O projeto base é um sistema integrado para atendimento de solicitações internas de suporte técnico, onde colaboradores podem registrar suas solicitações e uma inteligência artificial (IA) sugere soluções automáticas ou encaminha ao técnico adequado.

## 🎯 Objetivo

O principal objetivo deste repositório é demonstrar a aplicação das seguintes boas práticas:

*   **Documentação abrangente**: Fornecer um `README.md` detalhado que explique o projeto, sua estrutura, como executá-lo e as decisões de design.
*   **Padronização de Commits**: Utilizar um padrão de mensagens de commit claro e consistente para facilitar a rastreabilidade e compreensão do histórico do projeto.
*   **Estratégia de Branching**: Adotar uma estratégia de branch que permita o desenvolvimento organizado e a colaboração (mesmo que simulada para um projeto individual).
*   **Uso Eficiente do Git**: Empregar `.gitignore` e outras práticas recomendadas para manter o repositório limpo e focado no código relevante.

## 👨‍💻 Equipe (Referência do Projeto Original)

Este projeto é baseado em um trabalho em grupo, e a equipe original era composta por:

*   **PO**: Ana Clara Leão Ferreira
*   **Scrum Master**: Igor Sene Idalgo
*   **Devs**: Mauricio R. Verdussen, Pedro Henrique T. de Carvalho, Henry M. Damasceno Santos, Vinícius Gobis Novo

## 📋 Requisitos do Sistema

### Funcionais

*   **Cadastro de usuário**: Usuários podem se cadastrar no sistema.
*   **Autenticação de login**: Diferentes níveis de acesso.
*   **Abertura de chamados**: Usuários podem registrar requisições de suporte.
*   **Classificação inteligente**: IA analisa chamados e sugere soluções ou encaminha ao técnico adequado.

### Não Funcionais

*   **Banco de dados**: SQL Server.
*   **Segurança**: Implementação de medidas de segurança.
*   **Modularidade**: Design modular do sistema.

## 🚀 Backlog do Produto e Sprints (Referência do Projeto Original)

O projeto original foi dividido em sprints, com os seguintes objetivos e entregas:

| Sprint | Período | Objetivos | Entregas |
| :--- | :--- | :--- | :--- |
| **Sprint 1** | 03/06 - 09/06/2024 | Infraestrutura e base do sistema | Ambiente, DB, segurança inicial |
| **Sprint 2** | 10/06 - 16/06/2024 | Cadastro e autenticação | Cadastro + login |
| **Sprint 3** | 17/06 - 23/06/2024 | Abertura de chamados | CRUD de chamados |
| **Sprint 4** | 24/06 - 30/06/2024 | Classificação inteligente | IA treinada + sugestões |
| **Sprint 5** | 01/07 - 07/07/2024 | Refinamento e testes | Sistema ajustado + documentação |

## 📚 Modelagem de Requisitos (Referência do Projeto Original)

### 🔹 Casos de Uso

Fluxo:

1.  Funcionário faz login → abre chamado
2.  IA recebe e valida chamado
3.  IA define prioridade (alta, média, baixa)
4.  IA resolve ou encaminha ao técnico
5.  Chamado encerrado

### 🔹 Diagrama de Classes

Representa a estrutura do sistema, com suporte da IA para triagem, histórico e priorização dos chamados.

### 🔹 Diagrama de Sequência

### 🔹 Diagrama de Implantação

Representa a arquitetura do sistema de chamados com IA.

## 🛠️ Tecnologias Utilizadas (Referência do Projeto Original)

*   **SQL Server** – banco de dados
*   **(Definir linguagens/frameworks usados, ex: C#, .NET, Java, Node.js, etc.)**
*   **Ferramentas de versionamento**: Git/GitHub

## ▶️ Como Executar o Projeto (Referência do Projeto Original)

```shell
# Clonar repositório
git clone https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto

# Entrar na pasta do projeto
cd Atividade-da-disciplina-ASOO-projeto

# (Rodar comandos de instalação conforme a tecnologia escolhida)
```

## 💡 Boas Práticas Implementadas Neste Repositório Individual

### Padrão de Mensagens de Commit

Este repositório adota o seguinte padrão de mensagens de commit, baseado nas diretrizes do guia:

`<tipo> (<id_demanda>): <descrição da entrega feita no commit>`

**Tipos de Commit:**

*   `feat`: Uma nova funcionalidade.
*   `fix`: Uma correção de bug.
*   `docs`: Alterações na documentação.
*   `style`: Mudanças que não afetam o significado do código (espaços em branco, formatação, ponto e vírgula ausente, etc.).
*   `refactor`: Uma mudança de código que não adiciona uma funcionalidade nem corrige um bug.
*   `test`: Adição de testes ausentes ou correção de testes existentes.
*   `chore`: Outras mudanças que não modificam arquivos de `src` ou `test`.

**Exemplos:**

*   `feat (ASOO-001): Implementa funcionalidade de cadastro de usuários`
*   `fix (ASOO-002): Corrige erro de autenticação na tela de login`
*   `docs (ASOO-003): Atualiza seção de requisitos no README`

### Estratégia de Branching

Para este repositório individual, será utilizada uma variação simplificada do **GitHub Flow**:

*   A branch `main` será sempre a versão estável do projeto.
*   Para cada nova funcionalidade ou correção, uma nova branch será criada a partir de `main` (ex: `feature/nome-da-funcionalidade` ou `bugfix/descricao-do-bug`).
*   O desenvolvimento ocorrerá nessas branches separadas.
*   Após a conclusão e testes, as alterações serão mescladas de volta para `main` através de um Pull Request (simulado, se necessário, para fins de demonstração).

### Arquivo `.gitignore`

Um arquivo `.gitignore` foi configurado para ignorar arquivos e diretórios que não devem ser versionados, como:

*   Arquivos de cache e compilação (`__pycache__`, `build/`)
*   Ambientes virtuais (`venv/`, `.env/`)
*   Arquivos de log (`*.log`)
*   Arquivos específicos de sistema operacional (`.DS_Store`)
*   Arquivos de diagramas (`*.asta`, `*.jpg`, `*.png`) - *Nota: Estes foram incluídos no `.gitignore` para focar no código-fonte e documentação, mas podem ser versionados se forem parte integrante do projeto e não apenas artefatos gerados.*

