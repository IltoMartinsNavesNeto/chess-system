<h1 align="center">Jogo de Xadrez em Java</h1>

Este é um projeto de um jogo de xadrez simples desenvolvido em Java, jogado no terminal do gitbash. Ele utiliza uma notação de texto para representar o tabuleiro e as peças, permitindo que os jogadores façam movimentos de acordo com as regras do xadrez.

## Representação das Peças

No tabuleiro, as peças são representadas por letras, seguindo o padrão internacional para identificar cada uma delas:

- **R** - Torre (Rook)
- **N** - Cavalo (Knight)
- **B** - Bispo (Bishop)
- **Q** - Rainha (Queen)
- **K** - Rei (King)
- **P** - Peão (Pawn)

## Como Jogar

1. Clone o repositório:
   ```bash
   git clone https://github.com/IltoMartinsNavesNeto/chess-system-design-java.git
   cd chess-system-design

2. Compile o código 
   ```bash
   javac src/*.java

3. Execute o jogo
   ```bash
   java src.application

O tabuleiro será exibido no terminal. Em cada turno, você será solicitado a inserir o movimento da peça. Insira as coordenadas de origem e destino no formato e2 e4 para mover, por exemplo, um peão.

## Exemplo de Tabuleiro

O tabuleiro inicial é exibido no terminal da seguinte maneira:

  ![image](https://github.com/user-attachments/assets/a5b60a41-f1dc-46ee-957f-7322913b05d4)

O jogo mostra a lista de peças capturadas por cada jogador, o turno atual, e qual jogador está aguardando a jogada.

## Funcionalidades

- Movimentação das peças de acordo com as regras do xadrez.
- Indicação do turno e do jogador atual.
- Lista de peças capturadas.
- Atualização do tabuleiro após cada movimento.

## Exemplo de Jogadas

Este comando moverá o peão branco da casa e2 para a casa e4. O tabuleiro será atualizado automaticamente após a jogada.
Para realizar uma jogada, insira a coordenada de origem e destino no prompt do terminal:

   ```bash
   Turn: 1
   Waiting player: WHITE
   Source: e2 e4
  



