A fúria das.    profundezas

A história se passa em um tempo medieval, onde os personagens principais são um lenhador e seus 2 filhos que vivem próximos do vilarejo Pedra Fina. O vilarejo está sendo constantemente atacado pelos monstros que vivem na caverna próxima a cidade, e sua missão é acabar com essa ameaça…

Introdução:
começamos criando uma função de introdução que explica o que é o jogo e qual será sua missão

Lista de personagens:

Criamos uma lista de dicionários com os personagens jogáveis e seus status, para o jogador escolher o que mais o agradar. 

Depois criamos uma lista de dicionário de inimigos com seus status para serem apresentados mais à frente no jogo.

Escolha de personagem:
Usamos print para mandar a mensagem “Escolha seu personagem” ao jogador. O sistema inicialmente é operado por For i In.

com input nós fazemos a escolha do personagem com a mensagem “digite o número do player escolhido”





Sistema de batalha:

Criamos a função def batalha e apresentamos o inimigo, conforme o dicionário criado anteriormente.
usamos f para chamar a variável e print para apresentar o oponente, com um input de escolha após a mensagem.

o jogador usa if para decidir se vai atacar ou fugir do inimigo, em seguida utilizamos while para que enquanto a vida do jogador for maior ou igual ao ataque inimigo( ou vice-versa) vai continuar a batalha , e então utilizamos outro if para verificar se o hp do player for menor ou igual ao ataque inimigo, ele retorna a mensagem (você perdeu).
Em seguida, outra verificação, porém usando Elif para ter o mesmo mecanismo que o player tem, retornando a mensagem (você ganhou).
Por último, usamos eles em caso de empate.

itens e inventário:
Criamos uma lista de dicionário com itens e suas especificações, e uma lista vazia que seria o inventário do player.

O jogador vai poder encontrar três itens durante sua jornada.

Sistema de caminhos:
Criamos uma função usando def para que o jogador possa ter opção de seguir caminhos diferentes no seu jogo, usando print com uma mensagem “você encontrou alguns caminhos para seguir” assim também usamos o print para que o jogador faça sua escolha.

Em um dos caminhos sempre vai estar um dos chefes do jogo! E ao derrotá-lo você encontrará um item especial.
