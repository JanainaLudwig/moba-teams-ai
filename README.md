# Modelagem

- Espaço de busca: todas as possíveis combinações com 5 jogadores

- Solução: array com 5 elementos, representando o id de cada jogador. Cada elemento representa uma posição no jogo [sup, adc, jg, mid, top]
Por exemplo: [1, 2, 5, 8, 9]

- Estratégia de expansão da vizinhança: Alterar um dos elementos por um outro aleatório, porém priorizando um jogador da posição adequada.

- Função objetivo: 

- Critério de parada: número de iterações
