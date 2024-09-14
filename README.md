# Pong Clone
Este é um projeto simples que recria o clássico jogo Pong, desenvolvido em JAVA. O objetivo é aprender e praticar conceitos de programação de jogos 2D, como movimentação de objetos, detecção de colisões, e controle por teclado.

## Sobre o pong
Pong éum dos primeiros videogames já criados, lançado em 1972 pela Atari. O jogo simula um tênis de mesa, onde dois jogadores controlam barras que movem-se verticalmente nas extremidades da tela, com o objetivo de acertar uma bola e evitar que ela passe para o lado oposto.

## Desenvolvimento
Este projeto recria o Pong com as seguintes funcionalidades:
  - **Jogador vs. Computador**: O jogador controla a barra azul na parte inferior da tela, enquanto o inimigo (computador) controla a barra vermelha na parte superior.
  - **Movimentação e colisões**: A bola se move e rebate nas paredes laterais e nas barras dos jogadores. Quando a bola passa por uma das bordas superior ou inferior, o jogo é reiniciado e o ponto é atribuído ao adversário.
  - **Velocidade e ângulos**: A bola tem uma velocidade variável e a direção muda aleatoriamente após colisões com as barras dos jogadores.

## Executando o projeto
Para executar este projeto, você precisa ter o JDK instalado. Compile o código e execute a classe `game` para iniciar o jogo.

```bash
javac -d bin src/pong/*.java
java -cp bin pong.game
```

## Exemplo de jogo em execução

Aqui está um exemplo de como o jogo se parece:
  <p align="center">
    <img width="600" src = "README-INF/GIFs/PONG.gif">
  </p>

## Scripts

- `game.java`: Classe principal que gerencia o loop do jogo, renderização e entrada do jogador.
- `Player.java`: Controla o movimento da barra do jogador.
- `Enemy.java`: Controla o movimento da barra do inimigo (computador).
- `ball.java`: Controla o comportamento da bola, incluindo colisões e movimentação.

<br><br><br>
<p align="justify">
  Este projeto foi desenvolvido durate o Curso Desenvolvimento de Games Completo <br>
  Curso da Danki.Code: https://cursos.dankicode.com/curso-dev-games
</p>
Módulo 11: Criando jogo pong (Bônus), aulas:<br>
  - Criando jogo pong 1/3
  - Criando jogo pong 2/3
  - Criando jogo pong 3/3