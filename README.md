# Jogo da Velha (Tic-Tac-Toe) em C

Este repositório contém o código-fonte de uma implementação simples do jogo da velha (Tic-Tac-Toe) em C.
O jogo é para dois jogadores que se alternam entre as jogadas, sendo um jogador 'X' e o outro 'O'. O objetivo é preencher uma linha, coluna ou diagonal com o símbolo do jogador para vencer.

## Descrição
O código implementa o jogo da velha com as seguintes funcionalidades:

Tabuleiro de 3x3 (padrão do jogo da velha).
Permite a alternância entre dois jogadores, 'X' e 'O'.
Valida as jogadas, impedindo que o jogador faça uma jogada em uma posição já ocupada.
Verifica se há um vencedor após cada jogada ou se o jogo terminou em empate.
Exibe o tabuleiro após cada jogada e o resultado final (vencedor ou empate).

### Como rodar

1.Clone este repositório em sua máquina:
git clone https://github.com/seu-usuario/jogo-da-velha.git

2.Acesse o diretório do repositório:
cd jogo-da-velha

3.Compile o código usando o compilador gcc:
gcc -o jogo_da_velha jogo_da_velha.c

4.Execute o jogo:
./jogo_da_velha

## Estrutura do código
O código é dividido em algumas partes principais:

Definições de constantes:

* JOGADOR_X:  Define o símbolo do jogador X ('X').
* JOGADOR_O:  Define o símbolo do jogador O ('O').
* EMPATE:  Define o valor para indicar empate ('E').
* CARACTERE_BRANCO:  Define o caractere para espaços vazios no tabuleiro ('_').
* QTD_LINHAS e QTD_COLUNAS: Definem o número de linhas e colunas do tabuleiro (3x3).

## Como jogar
O tabuleiro será exibido no formato de uma matriz 3x3, onde cada célula é representada por _ (caractere em branco).
O jogador 'X' começa a partida, e em seguida, o jogador 'O' joga.
Durante sua vez, cada jogador deve digitar um número de 1 a 9 correspondente a uma posição no tabuleiro (1 para a posição superior esquerda, 9 para a posição inferior direita).
O jogo continua até que um jogador vença ou o jogo termine em empate.
O tabuleiro será exibido após cada jogada, e o resultado final será mostrado ao término da partida.
Exemplo de como o tabuleiro aparece:
_ _ _ |
_ _ _ |
_ _ _ |

Após algumas jogadas, o tabuleiro pode ficar assim:
X O X 
_ X O 
O _ X

### Regras do Jogo
** Vencer: ** Um jogador vence se conseguir alinhar 3 de seus símbolos em uma linha, coluna ou diagonal.
Empate: O jogo termina em empate se o tabuleiro estiver cheio e ninguém tiver vencido.
