# Capítulo 7: História de usuário, BDD e componentes

## Ideia central

Uma história é um dispositivo de alinhamento: conecta quem precisa, o que precisa e por quê, apoiada por conversa, exemplos verificáveis, tarefas e interface quando necessários.

## Frameworks introduzidos

- **Formato de história**: `Como <persona>, quero <PBI>, para <benefício>`.
- **3 Cs**:
  - **Cartão**: registro breve que convida à conversa.
  - **Conversa**: esclarece contexto, solução e limites.
  - **Confirmação**: critérios que demonstram satisfação.
- **BDD**: descreva comportamento por exemplos `Dado / Quando / Então`.
- **Critérios de aceite**: condições verificáveis específicas da história.

## Conceitos-chave

- **Habilitador**: trabalho técnico necessário para viabilizar valor; mantenha vínculo explícito com histórias beneficiadas.
- **Tarefa**: passo de implementação derivado da história.
- **Interface**: representação suficiente para alinhar interação; fidelidade depende do acordo do time.

## Modelos mentais

- O cartão não substitui conversa.
- Escreva critérios como exemplos observáveis, não instruções internas de implementação.
- Use apenas o nível de detalhe de interface que deixa o grupo confortável para começar.

## Antipadrões

- **História como contrato**: texto enorme não elimina necessidade de colaboração.
- **Persona genérica**: “usuário” esconde necessidades diferentes.
- **Critério subjetivo**: “ser fácil” não permite confirmação.
- **Habilitador órfão**: trabalho técnico sem relação com resultado do produto.

## Exemplo trabalhado

História: “Como participante, quero confirmar presença para manter meu histórico atualizado.” Critério BDD: dado que o participante está inscrito e o evento está aberto, quando confirmar presença, então o evento aparece em seu histórico. A conversa ainda decide exceções, interface e tarefas.

## Principais conclusões

1. Conecte persona, ação e benefício.
2. Use exemplos para tornar expectativas testáveis.
3. Registre tarefas e interface sem perder o propósito da história.

## Conecta-se a

- **ch08**: montagem colaborativa a partir do Canvas.
- **ch06**: critérios e dependências compõem Ready.
