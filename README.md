# :books: bdd-gherkin-examples

Este repositório é um acervo de estudos focado em Behavior Driven Development (BDD) utilizando a linguagem **Gherkin**. O objetivo é disponibilizar cenários realistas e bem estruturados de funcionalidades comuns em aplicações web, como login, cadastro, carrinho de compras, filtros de produtos, entre outros. 

Os arquivos estão separados por funcionalidade, em formato `.feature`, e podem ser utilizados como base para testes automatizados com **Cucumber** e **Cypress + Cucumber**.

---

## :question: O que é Gherkin?

**Gherkin** é uma linguagem estruturada de texto que segue um formato padronizado, usada para descrever o comportamento de um sistema em forma de exemplos. Ela permite que pessoas técnicas e não-técnicas possam entender e validar as regras de negócio de forma simples.

### :key: Palavras-chave principais:

![Gherkin Keywords](https://miro.medium.com/v2/resize:fit:828/format:webp/1*jUv3tJzUeYwoVuWYyAYLRA.png)

- **Feature:** Descreve uma funcionalidade do sistema
- **Scenario:** Um exemplo específico de uso
- **Given:** Estado inicial do sistema (contexto)
- **When:** Ação realizada pelo usuário
- **Then:** Resultado esperado
- **And / But:** Complementos para tornar a leitura fluida

---

## :thinking: Diferença entre BDD e Gherkin

| Conceito | Definição |
|---------|-----------|
| **BDD** (Behavior Driven Development) | É uma metodologia de desenvolvimento orientada a comportamentos. O foco está em entender o "**o quê**" o sistema deve fazer, a partir da colaboração entre desenvolvedores, QA e stakeholders. |
| **Gherkin** | É a linguagem usada para escrever os cenários de teste dentro do contexto do BDD. Ou seja, o Gherkin é a ferramenta textual que viabiliza o BDD na prática. |

> 🌟 **Resumo**: BDD é a abordagem, Gherkin é a linguagem que usamos para documentar os comportamentos.

---

## :open_file_folder: Estrutura do Repositório

```bash
.
├── features
│   ├── login.feature
│   ├── cadastro.feature
│   ├── recuperacao_senha.feature
│   ├── carrinho.feature
│   ├── filtros.feature
│   ├── perfil.feature
│   ├── acesso_restrito.feature
│   ├── cupom_desconto.feature
│   ├── email_boas_vindas.feature
│   ├── ordenacao_preco.feature
│   ├── endereco.feature
│   └── limite_tentativas.feature
├── README.md
```

Cada arquivo `.feature` possui cenários variados, contemplando casos de sucesso, falha, comportamentos esperados e mensagens de erro.

> 🔄 **Quer adicionar mais cenários?** Basta abrir o arquivo `.feature` da funcionalidade correspondente e incluir novos `Scenario` seguindo o mesmo padrão. Se for uma nova funcionalidade, crie um novo arquivo `.feature` dentro da pasta `/features`.

---

## :sparkles: Por que estudar com cenários Gherkin?

- Ajuda a visualizar o comportamento do sistema antes mesmo de codar
- Facilita a comunicação entre times (Dev, QA, PO...)
- Pode ser usado para testes manuais ou automatizados
- Torna o sistema mais previsível e confiável

---

## :construction: Em desenvolvimento

Este repositório está sendo construído com carinho para ajudar iniciantes a praticar escrita de cenários, simular testes e estruturar um portfólio. Contribuições, sugestões e feedbacks são super bem-vindos! 

Se você está começando agora, fique à vontade para clonar, adaptar e brincar com os cenários :blush:

> 🧩 **Quer contribuir?** Basta criar um novo arquivo `.feature` ou adicionar novos cenários aos arquivos existentes. O importante é seguir o padrão e manter a organização!

---

## :link: Referências

- https://cucumber.io/docs/gherkin/
- https://martinfowler.com/bliki/BDD.html
- https://testautomationu.applitools.com/bdd-tutorial/
- https://automationpanda.com/

---

Feito com :heart: por uma aprendiz apaixonada por qualidade de software.



