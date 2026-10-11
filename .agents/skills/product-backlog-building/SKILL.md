---
name: product-backlog-building
description: "Knowledge base from Product Backlog Building by Fábio Aguiar and Paulo Caroli. Use when collaboratively creating, refining, prioritizing, or checking a product backlog with PBB Canvas, Steps Map, COORG, Backlog Ready, user stories, BDD, TAPAs, and Lean Inception."
---

<!-- argument-hint: [tópico, framework ou capítulo] -->

# Product Backlog Building

**Autores**: Fábio Aguiar e Paulo Caroli | **Páginas**: ~148 | **Capítulos**: 10 | **Gerado**: 2026-08-13

## Como usar esta skill

- Sem argumento: carregue os modelos centrais abaixo.
- Com um tópico: consulte o capítulo indicado no índice antes de responder.
- Com `chNN`: leia diretamente o arquivo daquele capítulo.
- Ao facilitar uma sessão, use também [cheatsheet.md](cheatsheet.md).

## Modelos e frameworks centrais

### PBB: entendimento compartilhado antes da lista

Use Product Backlog Building para construir e refinar o Product Backlog de forma colaborativa. O resultado não é apenas uma lista: participantes compreendem produto, personas, funcionalidades e itens de trabalho. Prefira reunir quem trabalhará no produto a delegar toda a escrita à Product Owner.

Trate itens como hipóteses em contextos complexos. Construa apenas o backlog mínimo necessário para começar, entregue incrementos, busque feedback e atualize o backlog com o aprendizado.

### Fluxo do PBB Canvas

Siga a rastreabilidade do contexto ao trabalho:

1. Contextualize o produto com nome, problemas e expectativas.
2. Descreva personas, o que fazem e o que esperam.
3. Identifique funcionalidades: ações/interações da persona com o produto.
4. Explicite o benefício ou problema resolvido por cada funcionalidade.
5. Identifique PBIs usando `Ação → Resultado → Objeto`.
6. Use Steps Map para ordenar os passos necessários à completude de cada funcionalidade.
7. Organize visualmente `persona → funcionalidade → PBIs`.

Não confunda Steps Map com jornada: a jornada descreve o que o usuário faz para atingir um objetivo; o Steps Map descreve o que precisa ser construído para completar uma funcionalidade.

### COORG: Classificar, Ordenar e Organizar

Use COORG quando a lista de PBIs precisa virar uma ordem de trabalho:

- **Classificar**: o grupo define critérios, escalas e fórmula antes de pontuar. Exemplo do livro: `prioridade = frequência de uso + valor de negócio`; adapte ao contexto.
- **Ordenar**: disponha funcionalidades da esquerda para a direita segundo uma narrativa lógica, jornada ou sequenciador.
- **Organizar**: coloque PBIs de maior pontuação acima; leia a matriz da esquerda para a direita e de cima para baixo.

Reclassifique novos itens sem interromper a Sprint atual. Itens de baixo valor podem ficar fora; dependências e habilitadores devem ser considerados explicitamente.

### Backlog Ready e refinamento contínuo

Use Definition of Ready como acordo de entrada e Definition of Done como acordo de saída. Um PBI candidato deve ser compreendido, demonstrável, relacionado a uma funcionalidade e pequeno o bastante para uma Sprint. Refine continuamente os próximos candidatos; não transforme o PBB inicial em plano definitivo.

### História de usuário, 3 Cs e BDD

Uma história conecta `persona + PBI + benefício`: `Como <persona>, quero <ação>, para <benefício>`. O cartão é convite à conversa, não especificação completa. Use os 3 Cs — Cartão, Conversa e Confirmação — e registre critérios de aceite.

Quando útil, escreva exemplos BDD em `Dado / Quando / Então` para esclarecer comportamento verificável. Separe habilitadores técnicos e tarefas sem perder a ligação com o valor para o usuário.

### TAPAs

Dê o “tapa final” em cada história:

- **Tangível**: concreta e específica.
- **Atômica**: pequena e independente.
- **Preciosa**: resolve problema importante e explicita benefício.
- **Acessível**: simples e fácil de entender.

Votos vermelhos são gatilhos de conversa e revisão, não mera reprovação.

### PBB depois da Lean Inception

Use Lean Inception para alinhar MVP e funcionalidades; use PBB em seguida para quebrá-las em histórias e planejar próximas Sprints. Reaproveite personas e funcionalidades do Canvas MVP e a ordem do sequenciador; depois aplique Steps Map e COORG no nível dos PBIs.

## Índice de capítulos

| # | Título | Frameworks principais |
|---|---|---|
| [ch01](chapters/ch01-motivacao-e-fundamentos.md) | Motivação e fundamentos | entendimento compartilhado, backlog mínimo |
| [ch02](chapters/ch02-o-protagonista-backlog.md) | O protagonista: o backlog | hipóteses, granularidade |
| [ch03](chapters/ch03-metodo-pbb.md) | Product Backlog Building | colaboração, facilitação |
| [ch04](chapters/ch04-pbb-canvas-e-steps-map.md) | PBB Canvas e fluxo | Canvas, Ação–Resultado–Objeto, Steps Map |
| [ch05](chapters/ch05-coorg.md) | COORG | classificar, ordenar, organizar |
| [ch06](chapters/ch06-backlog-ready.md) | PBB e Backlog Ready | DoR, DoD, refinamento contínuo |
| [ch07](chapters/ch07-historias-bdd-e-componentes.md) | Histórias, BDD e componentes | 3 Cs, critérios, habilitadores |
| [ch08](chapters/ch08-escreva-historias-com-pbb.md) | Escreva histórias com PBB | persona + PBI + benefício |
| [ch09](chapters/ch09-tapas.md) | PBB e TAPAs | Tangível, Atômica, Preciosa, Acessível |
| [ch10](chapters/ch10-lean-inception.md) | PBB e Lean Inception | MVP → funcionalidades → PBIs |

## Índice de tópicos

- **Ação → Resultado → Objeto** → ch04
- **Backlog como hipóteses** → ch02
- **BDD / Dado-Quando-Então** → ch07
- **COORG** → ch05
- **Definition of Done / Ready** → ch06
- **Facilitação** → ch03, ch04
- **História de usuário** → ch07, ch08
- **Lean Inception e MVP** → ch10
- **PBB Canvas** → ch04
- **Steps Map** → ch04, ch10
- **TAPAs** → ch09

## Arquivos de apoio

- [glossary.md](glossary.md) — termos essenciais
- [patterns.md](patterns.md) — técnicas aplicáveis
- [cheatsheet.md](cheatsheet.md) — decisões e roteiro de facilitação

## Escopo e limites

Esta skill sintetiza o conteúdo do livro para estudo e aplicação. Adapte critérios, escalas, checklists e agenda ao contexto do produto e aos acordos do time.
