# Proposta Inicial do Jogo

Este documento deve ser preenchido pelo grupo na Semana 1 do projeto.

## 1. Nome provisório do jogo

> Alien Escape

## 2. Integrantes do grupo

- Nome 1: Matheus Henrique
- Nome 2: Diego Ribeiro
- Nome 3: Eduardo

## 3. Tipo de jogo

Tipo escolhido pelo grupo:

> Jogo de sobrevivência simples e desvio de obstáculos (runner infinito).

## 4. Descrição geral do jogo

Descrição:

> O jogador controla um militar que corre automaticamente por um cenário. Durante a partida, aliens aparecem no chão e OVNIs aparecem no céu. O jogador deve pular ou agachar para evitar os obstáculos e sobreviver o maior tempo possível. A dificuldade aumenta gradativamente conforme a partida avança.

## 5. Objetivo do jogador

Objetivo:

> Sobreviver o maior tempo possível desviando dos aliens e OVNIs, acumulando a maior pontuação possível.

## 6. Regras principais

Regras do grupo:

- O militar corre automaticamente durante toda a partida.
- Aliens aparecem no chão e devem ser evitados com pulos.
- OVNIs aparecem no céu e devem ser evitados ao se agachar.
- A pontuação aumenta conforme o tempo de sobrevivência.
- A partida termina ao colidir com qualquer obstáculo.

## 7. Condição de vitória

Condição de vitória:

> Como o jogo é infinito, não há uma vitória final. O objetivo é alcançar a maior pontuação possível e superar o recorde.

## 8. Condição de derrota ou encerramento

Condição de derrota ou encerramento:

> O jogo termina quando o jogador colide com um alien ou um OVNI.

## 9. Elementos previstos no jogo

### Jogador ou elemento principal

Descrição:

> Um militar controlado pelo jogador, capaz de pular e agachar para evitar obstáculos.

### Obstáculos, inimigos ou desafios

Descrição:

> Aliens terrestres que aparecem no chão e OVNIs que aparecem voando pelo céu.

### Itens, alvos ou objetos de interação

Descrição:

> Não haverá itens coletáveis na versão inicial. O foco será a sobrevivência e a pontuação baseada no tempo.

### Pontuação, vidas, tempo ou progresso

Descrição:

> A pontuação aumenta conforme o tempo de sobrevivência. O jogador possui apenas uma vida e perde ao colidir com um obstáculo.

## 10. Controles previstos

Controles do grupo:

- Espaço: pular.
- Seta para baixo (↓): agachar.
- ENTER: reiniciar a partida.

## 11. Organização inicial do código

Organização planejada:

- `main.py`: inicia o jogo.
- `src/jogo.py`: contém o loop principal.
- `src/jogador.py`: controla o militar.
- `src/obstaculos.py`: controla aliens e OVNIs.
- `src/config.py`: configurações gerais do jogo.
- `src/dados.py`: armazenamento de recordes.

## 12. Recursos externos previstos

Recursos previstos:

- Imagens gratuitas para o militar, aliens e OVNIs.
- Sons gratuitos para pulo e colisão.
- Fonte gratuita para exibição da pontuação.
- Tutoriais sobre Pygame utilizados apenas como referência.

## 13. Principais dificuldades esperadas

Dificuldades previstas:

- Implementação da colisão entre jogador e obstáculos.
- Controle do pulo e da ação de agachar.
- Aumento progressivo da dificuldade e velocidade do jogo.

## 14. Escopo mínimo para a entrega final

Escopo mínimo:

> A versão mínima do jogo terá um militar controlado pelo teclado, aliens e OVNIs surgindo como obstáculos, sistema de pontuação baseado no tempo, detecção de colisões e tela de fim de jogo.

## 15. Possíveis melhorias, caso haja tempo

Melhorias possíveis:

- Sistema de ranking e recordes.
- Efeitos sonoros e músicas.
- Animações para o personagem e obstáculos.
- Tela inicial e menu de pausa.
- Diferentes tipos de aliens e OVNIs.