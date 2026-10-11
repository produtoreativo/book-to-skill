# Capítulo 5: COORG — técnica de priorização

## Ideia central

COORG converte a lista visual de PBIs em uma ordem de trabalho por meio de três ações: classificar, ordenar e organizar.

## Frameworks introduzidos

- **Classificar**:
  1. O grupo escolhe critérios relevantes.
  2. Define escalas e pesos antes de avaliar itens.
  3. Pontua cada PBI e registra o resultado.
- **Ordenar**: coloque funcionalidades da esquerda para a direita em narrativa lógica, jornada ou ordem do sequenciador; mova seus PBIs junto.
- **Organizar**: dentro de cada funcionalidade, posicione PBIs de cima para baixo, maior prioridade primeiro; leia a matriz por linha, da esquerda para a direita.

## Conceitos-chave

- **Frequência de uso**: exemplo de critério com escala hora a hora (5), diária (4), semanal (3), mensal (2), trimestral (1).
- **Valor de negócio**: exemplo de escala alto (3), médio (2), baixo (1).
- **Fórmula-exemplo**: `prioridade = frequência de uso + valor de negócio`.

## Modelos mentais

- Critérios são contextuais; não copie a fórmula sem discutir o que o produto valoriza.
- Baixa pontuação torna explícita a oportunidade de dizer “não”.
- Priorização é provisória: feedback cria novos itens que passam novamente pelo COORG.

## Antipadrões

- **Pontuar antes de alinhar critérios**: números escondem interpretações diferentes.
- **Pontuação como verdade matemática**: a fórmula apoia julgamento, não substitui decisões.
- **Novo item interrompe Sprint**: classifique-o para Sprint futura; preserve a Sprint atual.

## Exemplo trabalhado

Um PBI diário (4) e de alto valor (3) recebe 7. Outro usado hora a hora (5), mas de baixo valor (1), recebe 6. Após pontuar, o grupo ordena funcionalidades pela narrativa e organiza itens nas linhas 7, 6 etc. A primeira linha lida da esquerda para a direita fornece os primeiros candidatos.

## Principais conclusões

1. Defina critérios, escalas e fórmula coletivamente.
2. Combine prioridade numérica com narrativa e dependências.
3. Reaplique o método quando o backlog evoluir.

## Conecta-se a

- **ch04**: recebe os PBIs do Steps Map.
- **ch10**: prioriza histórias dentro das funcionalidades do MVP.
