# Capítulo 6: PBB e Backlog Ready

## Ideia central

A qualidade do fluxo depende de acordos explícitos na entrada e na saída: Definition of Ready prepara o trabalho; Definition of Done comprova o incremento concluído.

## Frameworks introduzidos

- **Definition of Ready (DoR)**: acordo entre time e PO para um item poder ser puxado.
  - Há informação suficiente, propósito compreendido, término demonstrável, relação com funcionalidade e tamanho compatível com uma Sprint.
  - Checklist-exemplo: história de usuário; critérios de aceite/BDD; interface quando necessária; dependências identificadas.
- **Definition of Done (DoD)**: acordo de qualidade para liberar o incremento.
  - Deve entregar incremento, cumprir critérios e padrões acordados e estar apto ao uso.
- **Refinamento contínuo**: preparar permanentemente os próximos candidatos, em vez de aguardar uma cerimônia tardia.

## Conceitos-chave

- **Ready**: informação suficiente para planejar, executar e entregar.
- **Done**: satisfação do acordo de conclusão; caso contrário, o item continua WIP.
- **Backlog inicial**: ponto de partida criado pelo PBB, não estado final.

## Modelos mentais

- Só deixe entrar o que está preparado e sair o que está pronto.
- Use checklists como acordos adaptáveis do time, não burocracia universal.
- Estruture novos itens conforme existam ou não persona e funcionalidade correspondentes; atualize o Canvas quando surgirem novos contextos.

## Antipadrões

- **Ready como aprovação externa**: deve apoiar conversa e fluxo do time.
- **Mostrar item não Done como concluído**: oculta WIP e compromete transparência.
- **Refinar uma vez**: o produto e o backlog são emergentes.

## Exemplo trabalhado

Antes do planejamento, o time verifica uma história: persona e benefício claros, cenários BDD, dependência identificada e interface combinada. Se não cabe na Sprint, é dividida. Após implementação, somente é liberada quando cumpre critérios e DoD do time.

## Principais conclusões

1. Ready reduz ambiguidade antes do compromisso.
2. Done protege qualidade e transparência.
3. Mantenha candidatos futuros continuamente refinados.

## Conecta-se a

- **ch07**: detalha os componentes da checklist.
- **ch09**: verifica atributos de qualidade antes da Sprint.
