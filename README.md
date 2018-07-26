# damas-simples
Jogo de Damas simples feito inteiramente em Java, JavaFX e SQLite.

Inicialmente, o projeto será feito com a interface gráfica de JavaFX.
Futuramente, deverá ser feito a versão Web dele, usando Angular e Spring.

Deverá ser usado o banco SQLite, ou MongoDB.

Siga o padrão MVC para criar o projeto, onde você criará os Models, Views e Controllers.
Procure usar Lambda, Métodos de Referências e Streams, tudo do Java 8 pra cima.

O jogo deverá seguir as regras oficiais :

http://www.damasciencias.com.br/regras/regras_do_jogo.html

E também deverá salvar os nomes dos jogadores no banco, com sua quantidade de vitórias e derrotas.
Também deve salvar no banco a quantidade de jogos que foi realizado no programa.

* Os nomes dos jogadores deverão ser inseridos no inicio do programa.
* O jogo será pro turnos.
* A cada turno, deverá mostrar o nome do jogador da rodada.
* No final da partida, mostrar quem ganhou e salvar as informações novas no banco.
* Se o jogo for fechado ou cancelado durante a partida, não salvará nenhuma informação.
