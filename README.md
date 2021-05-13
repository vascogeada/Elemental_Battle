# Elemental_Battle
Este projeto é feito no âmbito de Programação Orientado a Objetos e de Engenharia de Software.

Tema:
Criar um jogo de tabuleiro com o foco de envolver vários duelos entre 2 jogadores. 
  Esses duelos são representados pela utilização de cartas, sendo elas quantificadas pela sua força e destreza de 1 a 5. Podendo ou não ter capacidades (modificar atributos).
  
  
Objetivo:
  Obter 5 vitórias nas “casas duelo”, evitando perder os duelos.
  
Características:
  Dado de 1 a 6;
  Tabuleiro de 6x6 (20 casas);
  1 casa partida (posição onde o jogador começa);
  7 casas neutra (o jogador não pode fazer qualquer ação e passa o turno);
  8 casas duelo (o jogador é obrigado a entrar num duelo com o adversário);
  4 casas surpresa (nesta casa é testado a sorte do jogador, podendo sair dela beneficiado ou não);
  
  
Regras:
  Jogadores: 2
  O tabuleiro é dividido por 20 casas, 7 casas neutra, 8 casas duelo e 4 casas surpresa; 
  O jogador inicia com 15 cartas;
  Para ver quem ganha é medido a força, caso seja igual é medido pela destreza e em caso de empate nenhum jogador ganha o ponto;
  O jogador começa na “casa partida”;
  O jogador só pode lançar o dado uma vez por jogada;
  O jogador move-se de acordo com o resultado do lançamento dos dados;
  O jogador move-se pelo sentido dos ponteiros do relógio;
  As jogadas são alternadas;
  Na casa surpresa vai ser atribuido ao jogador, aleatóriamente, uma ordem para avançar ou recuar x casas, ou pode receber um bónus de força e/ou destreza numa carta à sua escolha;
  Na casa duelo o jogador é obrigado a enfrentar o adversário;
  Na casa neutra o jogador termina a sua vez;
  Cada vez que o jogador passa pela “casa partida”, recebe 1 carta aleatória;
  Cada carta pode ter ou não uma capacidade;
  Cada carta só pode ser utilizada uma vez, pois é descartada após o seu uso.
