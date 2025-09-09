# Como Contribuir

Este repositório é um projeto individual para fins de demonstração e aprendizado das boas práticas de Git e GitHub. No entanto, se este projeto fosse colaborativo, as seguintes diretrizes seriam aplicadas para contribuições:

## 🤝 Processo de Contribuição

1.  **Fork** o repositório.
2.  **Clone** o seu fork localmente.
3.  Crie uma **nova branch** para sua funcionalidade ou correção de bug (`git checkout -b feature/sua-funcionalidade` ou `git checkout -b bugfix/sua-correcao`).
4.  Faça suas alterações e **commits** seguindo o [Padrão de Mensagens de Commit](#padrão-de-mensagens-de-commit) descrito no `README.md`.
5.  Envie suas alterações para o seu fork (`git push origin feature/sua-funcionalidade`).
6.  Abra um **Pull Request (PR)** para a branch `main` deste repositório, descrevendo detalhadamente as alterações e os cenários de teste.
7.  Aguarde a **revisão do código** e feedback.

## ✨ Padrão de Mensagens de Commit

Por favor, siga o padrão de mensagens de commit:

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

## 📝 Boas Práticas

*   Mantenha seus commits pequenos e focados em uma única alteração.
*   Escreva mensagens de commit claras e concisas.
*   Certifique-se de que seu código esteja formatado corretamente.
*   Adicione ou atualize testes conforme necessário para suas alterações.
*   Evite fazer commit diretamente na branch `main`.

