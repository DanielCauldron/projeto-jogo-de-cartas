# projeto-jogo-de-cartas
 Criando um projeto de estudo Jogo de Cartas do Yu-Gi-Oh! com JavaScript e CSS

 O projeto de estudo é um jogo simples de cartas baseado em um sistema de duelos. Vou fornecer uma explicação passo a passo do código:

Definição do Estado Inicial (state):

O objeto state contém todas as informações sobre o estado atual do jogo, como pontuações, elementos do DOM e ações do jogo.
Dados das Cartas (cardData):

A matriz cardData contém informações sobre cada carta no jogo, como nome, tipo, imagem e relações de vitória e derrota com outras cartas.
Função getRandomCardId:

Retorna um ID de carta aleatório a partir do conjunto de dados.
Função createCardImage:

Cria dinamicamente elementos de imagem (cartas) e os associa a eventos do mouse.
Função setCardsField:

Inicia um novo duelo, definindo as cartas para o jogador e o computador.
Chama funções para atualizar a exibição das cartas, ocultar detalhes e verificar o resultado do duelo.
Função drawCardsInField:

Atualiza as imagens das cartas no campo de jogo.
Função showHiddenCardFieldsImages:

Controla a exibição/ocultação das cartas no campo de jogo.
Função hiddenCardDetails:

Limpa os detalhes da carta exibidos na interface.
Função drawButton:

Atualiza o texto do botão de ação e o exibe.
Função updateScore:

Atualiza a exibição da pontuação na interface.
Função checkDuelResults:

Verifica o resultado do duelo comparando as cartas escolhidas pelo jogador e pelo computador.
Atualiza a pontuação e reproduz um som correspondente.
Função removeAllCardsImages:

Remove todas as imagens de cartas do jogador e do computador.
Função drawSelectCard:

Exibe detalhes da carta quando o mouse paira sobre ela.
Função drawCards:

Gera e exibe um número específico de cartas no campo de jogo.
Função resetDuel:

Reinicia o estado do jogo, ocultando cartas e redefinindo a interface.
Função playAudio:

Reproduz um arquivo de áudio com base no resultado do duelo.
Função init:

Inicializa o estado inicial do jogo, exibindo ou ocultando elementos conforme necessário.
Gera cartas para o jogador e o computador.
Inicia a trilha sonora do jogo.
Chamada inicial da função init:

Inicia o jogo quando a página é carregada.
Este código utiliza a manipulação do DOM para interagir com elementos HTML, gera eventos com base nas ações do usuário e apresenta uma lógica simples de jogo.
[Clique aqui](https://danielcauldron.github.io/projeto-jogo-de-cartas/).
