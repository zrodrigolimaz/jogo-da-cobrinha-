# Prompt Detalhado: Jogo da Cobrinha

Desenvolva um jogo da cobrinha (Snake) em HTML, CSS e JavaScript puro. Todo o código deve estar em um único arquivo HTML funcional.

## Requisitos

1. **Controles**: Use as teclas W (cima), S (baixo), A (esquerda) e D (direita) para movimentar a cobrinha. Impedir que a cobra inverta a direção instantaneamente (ex: indo para direita, não aceitar tecla A).

2. **Pontuação**: Sistema de pontuação que aumenta quando a cobra come a comida. Exibir o placar em tempo real na interface.

3. **Crescimento**: A cobrinha deve crescer de tamanho (adicionar um segmento) cada vez que come a comida.

4. **Comida**: A comida deve aparecer em posições aleatórias do mapa, garantindo que não nasça em cima da cobra.

5. **Interface**: Interface simples com título, placar visível e área de jogo (canvas). Após game over, exibir mensagem e pontuação final.

6. **Reiniciar**: Botão para reiniciar o jogo após game over. O botão pode ficar visível apenas quando o jogo terminar.

7. **Game Over**: O jogo deve encerrar quando a cobra bater na parede ou no próprio corpo.

8. **Velocidade**: A velocidade deve aumentar gradativamente conforme o usuário coleta mais comida (ex: reduzir o intervalo do loop a cada 5 ou 10 pontos).

## Implementação técnica

- Use `<canvas>` para desenhar o jogo
- Grid sugerido: 20x20 células, cada célula com 20px
- Cobra representada por array de coordenadas
- Loop do jogo com `setInterval` ou `requestAnimationFrame`
