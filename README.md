# Intro_Comp_A2_
Trabalho final da disciplina Introdução à Ciência de Dados ministrada pelo professor Flávio.

- Integrantes
Alice Pereira de Aguilar Penido
Breno Marques Azevedo
Cleomar Felipe Rabelo Antoszczyszyn 
Gustavo Ramalho
João Victor Mendes

- Controles 
No nosso jogo é possível se movimentar para qualquer direção na tela, por meio das teclas WASD:
	W: Se mover para cima
	A: Se mover para a esquerda
	S: Se mover para baixo
	D: Se mover para a direita
	P: pausa o jogo	
	
	Também é possível atirar nas naves inimigas, por meio da barra de ESPAÇO.
	
	As naves inimigas surgem de forma aleatória em diferentes posições da tela e se movem para
	os lados e para baixo.

	Não é possível sair dos limites da tela do jogo.
	Você deve manter os botões pressionados para se movimentar.

- Como jogar
Basta desviar dos disparos e destruir as naves inimigas que virão na sua direção. 
Colidir com os disparos ou com as naves fará com que você leve dano.
Deixar que as naves chegem ao final da tela reduzirá o seu número de vidas.
	
- Inicialização do jogo
Após compilar o programa você verá uma nova janela aberta. Nela está o nosso jogo com o menu principal. 
Para começar a jogar, basta clicar com mouse - botão direito ou esquerdo. Assim, o jogo começará e você
já poderá se divertir.

- Função Pause
Ao pausar o jogo, você pode resumir clicando em qualquer tecla, exceto a tecla P, pois ela que aciona o pause.
Enquanto pausado, não é possível fechar o jogo. Para fechar, é necessário resumir o jogo e fechar normalmente.

- Sair e fechar o jogo
Para fechar o jogo, basta retornar ao menu principal - aquele que você viu assim que inicializou o programa -
e fechar a janela clicando no botão superior direito. Você retornará ao menu principal assim que perder toda
saúde ou todas as vidas ou simplesmente se clicar no botão de fechar da janela do Pygame durante uma partida.

- Requisitos do professor:
## Uso de sprites
	Utilizamos o pygame.sprite.Sprite em conjunto com o pygame.mask para reconhecer as colisões no jogo.

## Controle do movimento de sprites via código. [...] O movimento não deve ser apenas retilíneo, e deve conter algum elemento aleatório.
	Os sprites do jogo se movimentam na vertical (inimigos e disparos). Os disparos têm uma chance aleatória de acontecer.

## Controle de um sprite via teclado.
	O jogador se movimenta usando o teclado.

## Adiciona novos elementos gráficos, como sprites, telas, animações, etc.
	Adiconamos sprites diferenets e novas telas, bem como uma barra de saúde.

## Adiciona elementos sonoros, como Música ou sons.
	Adicionamos trilha e efeitos sonoros usando a classe mixer do pygame.

## Adiciona lógica nova como: transição visual de fase e função pausar jogo.
	Ambas essas características estão presentes no jogo.
