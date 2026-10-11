# Cheatsheet de decisão e facilitação

## Qual técnica usar?

| Situação | Faça | Porque |
|---|---|---|
| Não há entendimento comum do produto | PBB Canvas completo | Liga problemas, pessoas e trabalho |
| Funcionalidade ainda é grande | Steps Map | Expõe passos e candidatos a PBI |
| Há PBIs, mas não ordem | COORG | Torna critérios e sequência explícitos |
| Item vai entrar na Sprint | DoR + TAPAs | Verifica informação e qualidade |
| Comportamento está ambíguo | Critérios + BDD | Cria exemplos observáveis |
| MVP já foi alinhado | Encaixe Lean Inception → PBB | Reaproveita artefatos e detalha entrega |
| Novo item surgiu durante Sprint | Classifique no backlog futuro | Preserva o compromisso da Sprint atual |

## Fluxo de uma sessão PBB

1. Confirme objetivo, participantes e termos.
2. Nomeie produto; explicite problemas e expectativas.
3. Descreva personas: perfil, ações e expectativas.
4. Liste funcionalidades por persona e benefício.
5. Escreva PBIs como `Ação → Resultado → Objeto`.
6. Faça Steps Map para cada funcionalidade relevante.
7. Aplique COORG: Classificar → Ordenar → Organizar.
8. Monte histórias: persona + PBI + benefício.
9. Complete critérios, BDD, dependências e interface.
10. Verifique Ready e TAPAs; continue refinando depois.

## Decisões rápidas

- Se o item é incerto, trate como hipótese e defina feedback rápido.
- Se o backlog parece completo, procure itens distantes que podem ser adiados.
- Se ninguém explica o benefício, volte à funcionalidade, persona e problema.
- Se o PBI é um substantivo, reescreva como ação e resultado.
- Se dois termos causam conflito, alinhe níveis de abstração e escolha a linguagem do contexto.
- Se uma história não cabe na Sprint, quebre-a antes de considerá-la Ready.
- Se um habilitador não tem história beneficiada, questione sua prioridade.
- Se a pontuação decide tudo sozinha, retome critérios, dependências e julgamento da PO.
- Se há muitos votos TAPA vermelhos, revise; não pressione o grupo por unanimidade artificial.

## Escalas-exemplo do COORG

| Frequência | Nota | Valor de negócio | Nota |
|---|---:|---|---:|
| Hora a hora | 5 | Alto | 3 |
| Diário | 4 | Médio | 2 |
| Semanal | 3 | Baixo | 1 |
| Mensal | 2 |  |  |
| Trimestral | 1 |  |  |

`Prioridade = frequência de uso + valor de negócio` é apenas o exemplo do livro. Defina critérios, escalas e fórmula adequados ao produto antes de pontuar.

## Smells

| Sinal | Provável problema |
|---|---|
| Muitos itens “algum dia” | Estoque de desejos, não backlog mínimo |
| “Usuário” em toda história | Personas insuficientemente específicas |
| Benefício repete o PBI | Porquê ainda não compreendido |
| Canvas preenchido por uma pessoa | Falta de entendimento compartilhado |
| Tudo tem prioridade alta | Critérios ou escalas não discriminam valor |
| Item demonstrado mas não Done | WIP sendo tratado como conclusão |
