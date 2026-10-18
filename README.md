# Mesa de Rummi

Jogo de Rummi online para 2 a 8 pessoas, cada uma no seu aparelho, direto no navegador. Sem cadastro e sem instalar nada.

## Como jogar

1. Abra o site do jogo.
2. Escreva seu nome e toque em **Criar sala nova**.
3. Mande o código de 4 letras para a turma. Os outros abrem o mesmo site, escrevem o nome, digitam o código e entram.
4. Quem criou a sala começa a partida e precisa deixar a página aberta até o fim.

Também dá para **jogar sozinho contra robôs**, nos níveis fácil, médio e difícil.

## Regras

- Cada jogador recebe 14 peças. Até 4 jogadores a partida usa 106 peças; de 5 a 8, usa 212.
- **Sequência:** 3 ou mais números seguidos da mesma cor. **Grupo:** 3 ou 4 peças do mesmo número em cores diferentes.
- A primeira descida precisa somar 30 pontos, só com peças do seu suporte.
- Depois disso, dá para reorganizar a mesa à vontade, desde que tudo termine em combinações válidas.
- O coringa vale a peça que substitui. Se sobrar no suporte no fim, vale 30 pontos contra.
- Sem jogada, você compra uma peça. Ganha quem esvaziar o suporte primeiro.

## Recursos

- Tempo por jogada configurável (30 s a 3 min). Uma jogada válida é finalizada sozinha quando o tempo acaba.
- Arrastar peças com o dedo ou o mouse, inclusive várias de uma vez. No suporte, cada peça vai para qualquer posição.
- Os botões de organizar o suporte só juntam peças que já formam uma sequência ou um grupo válido.
- Trocar um coringa da mesa pela peça que ele representa solta o coringa numa combinação nova, pronta para completar.
- A mesa não aceita uma peça repetida (mesmo número e cor) numa combinação.
- Todos acompanham a jogada de quem está na vez, ao vivo.
- Chamada de voz entre os jogadores.
- Robôs para completar a mesa ou para treinar sozinho.

## Como funciona por dentro

O jogo inteiro é um único arquivo, `index.html`. As mensagens entre os jogadores passam por servidores públicos gratuitos (relays Nostr), sem servidor próprio. As peças de cada jogador são criptografadas, então só o dono vê o próprio suporte.
