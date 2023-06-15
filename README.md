# JOGO DA VELHA
Alunos: João Pedro Tonatto Fraga e Rafael da Cunha<br>
Professor: Jhonatan Alves<br>
Disciplina: Algoritmos e Programação I

## Sobre o projeto
Como o próprio nome diz, o código simula um jogo da velha que deverá ser realizado por dois jogadores no mesmo dispositivo. Criado em C, o programa é composto por 3 funções, sendo elas responsáveis por verificar se já há um vencedor na partida(que será iniciado depois da quinta rodada), gerar a interface do jogo e a principal sendo onde realmente ocorre o jogo.

## Como funciona
Ao iniciar o programa será neccesário inserir o nome dos dois jogadores que jogarão o jogo, em seguida, o jogador que inseriu o nome primeiro sempre será o primeiro a jogar, ou seja, se inserirmos os nomes joão(player1) e rafael(player2), o jogador joão começará jogando.

## Bugs
- Ao tentar colocar uma string em um espaço já preenchido, o jogo substituirá a antiga pela nova.
- Nessa versão, se o jogo passar da nona rodada automaticamente será declarado empate.

## Bibliotecas usadas
- Biblioteca padrão do C. (stdio.h)
- Biblioteca para usarmos a função de limpar o console durante o jogo (stdlib.h)
