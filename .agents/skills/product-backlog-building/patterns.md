# Padrões e técnicas

## Contexto → personas → funcionalidades → PBIs

**Quando usar**: ao criar ou reorganizar um backlog sem rastreabilidade clara.

**Como**: explicite problemas e expectativas; descreva personas; identifique suas funcionalidades e benefícios; quebre funcionalidades em PBIs.

**Trade-offs**: dá coerência e alinhamento, mas exige presença das perspectivas corretas e boa facilitação.

## Ação → Resultado → Objeto

**Quando usar**: quando PBIs estão vagos ou nomeados apenas com substantivos.

**Como**: escreva uma ação concreta que produza um resultado sobre um objeto; revise se outro participante entende o comportamento esperado.

**Trade-offs**: melhora clareza, mas não substitui critérios de aceite.

## Steps Map

**Quando usar**: para decompor uma funcionalidade em itens menores.

**Como**: descreva os passos até a completude, ordene-os, questione cada passo e transforme os necessários em PBIs.

**Trade-offs**: revela lacunas; pode virar jornada indevidamente se o grupo não mantiver foco no que precisa ser construído.

## COORG

**Quando usar**: quando existe uma lista de PBIs, mas falta ordem para planejamento e entrega.

**Como**: Classifique com critérios/escalas acordados; Ordene funcionalidades em uma narrativa; Organize PBIs verticalmente por prioridade.

**Trade-offs**: torna julgamento explícito; números podem criar falsa precisão se usados sem conversa.

## Checklist de Ready

**Quando usar**: antes de puxar um item para planejamento ou execução.

**Como**: confira história, benefício, critérios/BDD, interface necessária, dependências e tamanho; adapte o checklist ao time.

**Trade-offs**: reduz ambiguidade; pode virar barreira burocrática se tratado como aprovação rígida.

## História a partir do Canvas

**Quando usar**: após identificar e priorizar PBIs.

**Como**: combine persona (quem), PBI (o quê) e benefício (por quê) no formato `Como..., quero..., para...`; complete com conversa e confirmação.

**Trade-offs**: preserva rastreabilidade; um formato correto não garante uma boa história.

## Cenário BDD

**Quando usar**: quando exemplos concretos ajudam a esclarecer critérios de aceite.

**Como**: descreva contexto em `Dado`, evento em `Quando` e resultado observável em `Então`; cubra exemplos essenciais e exceções relevantes.

**Trade-offs**: torna expectativa verificável; excesso de cenários precoces pode congelar solução.

## Votação TAPAs

**Quando usar**: como revisão final de histórias candidatas à Sprint.

**Como**: cada pessoa avalia Tangível, Atômica, Preciosa e Acessível com verde/vermelho; discuta divergências e revise.

**Trade-offs**: expõe desalinhamento rapidamente; perde valor se votos forem usados só como gate.

## Encaixe Lean Inception → PBB

**Quando usar**: depois de alinhar um MVP.

**Como**: transfira personas e funcionalidades; preserve ordem do sequenciador; faça Steps Map e COORG; escreva histórias.

**Trade-offs**: liga estratégia à entrega; requer cuidado para não duplicar discussões já encerradas.
