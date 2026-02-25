# 🧩 Modos do Copiloto: O Cajado de Gandalf (Java & Spring Boot)

O Copiloto oferece diferentes **modos de interação** para você escolher como quer trabalhar: desde tirar dúvidas sem mexer no código, até editar trechos específicos, planejar mudanças maiores ou delegar tarefas mais complexas com um modo mais autônomo. A ideia é simples: você seleciona o modo que melhor combina com seu objetivo no momento e ganha velocidade com a sabedoria de um mestre.

---

### ❓ Ask
O modo **Ask** é para fazer perguntas e entender coisas, **sem alterar seu código**. Você pode perguntar sobre um arquivo específico, um erro (Stack Trace), uma função, uma lógica de negócio ou até conceitos gerais de Engenharia de Software.

O Gandalf lê o contexto do projeto e responde como um **“mentor técnico”**, lançando luz sobre o que está acontecendo e por quê. Ele não modifica nada — apenas analisa, explica e guia sua compreensão.
📄 **Prompt:** `prompts/prompt-ask.md`

### ✏️ Edit
O modo **Edit** serve para **alterar código existente**. Você seleciona um trecho (ou uma classe inteira), descreve o que quer mudar, e o Copiloto aplica a modificação diretamente no seu arquivo.

Ideal para:
* Refactors e limpeza de código (Clean Code)
* Ajustes de lógica em Services e Controllers
* Melhoria de performance em queries JPA/Hibernate
* Mudança de estilo ou conversão de boilerplate para Records
* Adicionar logs e tratamento de exceções globais
Aqui o foco é: **“Pegue este código que já existe e transforme-o”**.
📄 **Prompt:** `prompts/prompt-edit.md`

### 🧭 Plan
Quando você pede algo mais complexo, o Copiloto entra em um modo de **planejamento**, onde ele pensa e descreve o mapa da jornada antes de sair codificando.

Ele:
* Divide o problema em etapas lógicas
* Explica a estratégia e os padrões de projeto (Design Patterns)
* Só executa a implementação após você validar a abordagem
Isso é vital para **mudanças grandes**, novas features ou quando você quer validar a arquitetura na UFBRA antes de mexer no código.
📄 **Prompt:** `prompts/prompt-plan.md`

### 🤖 Agent
O **Agent** é o modo mais “autônomo”. Ele pode navegar pela estrutura do projeto Maven, **criar novos arquivos**, modificar múltiplos pontos simultaneamente e manter o contexto entre os passos, como um desenvolvedor sênior trabalhando ao seu lado.

Você dá um objetivo (ex.: “Implemente o módulo de autenticação com JWT”) e ele decide o que precisa ser forjado em vários arquivos para alcançar o resultado final.
📄 **Prompt:** `prompts/prompt-agent.md`

### 📚 Study
O modo **Study** é focado em **aprendizado ativo**, não apenas em chegar à resposta ou ao código final. Essencial para dominar os fundamentos exigidos na faculdade.

Em vez de simplesmente executar, ele:
* Ensina e guia o raciocínio com analogias da Terra-média
* Destaca conceitos fundamentais e trade-offs técnicos
* Faz perguntas reflexivas para testar seu conhecimento
* Avança conforme seu ritmo de aprendizado
Funciona como um **tutor particular de Java**.
📄 **Prompt:** `prompts/prompt-study.md`

---

### 🧠 Resumo mental rápido

* **Ask** → Entender o enigma
* **Plan** → Traçar o mapa antes de agir
* **Edit** → Transformar código existente
* **Agent** → Forjar novas funcionalidades sozinho
* **Study** → Entendimento ativo e sabedoria

---

> *"Tudo o que temos de decidir é o que fazer com o código que nos é dado."*
