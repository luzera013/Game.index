# Game.index
Idle de dinheiro simples e funcional.


prompt para o futuro idle

Crie um jogo idle 2D completo chamado "Empire World" que funcione no navegador usando HTML, CSS e JavaScript (preferencialmente com Canvas ou uma estrutura organizada de renderização).

🎮 CONCEITO:
O jogo deve combinar idle + exploração 2D, com foco em uma experiência leve, intuitiva e agradável. O jogador controla um personagem em um pequeno mundo interativo, evoluindo aos poucos sem exigir interação constante ou mecânicas excessivamente viciantes.

O progresso deve ser satisfatório, porém equilibrado, incentivando pausas naturais e sessões curtas de jogo.

🧍 PERSONAGEM:

* Personagem controlável (WASD ou setas)
* Movimento fluido e animação simples
* Sistema de personalização visual:

  * Roupas (skins)
  * Acessórios (chapéu, óculos, etc.)
* Itens equipados devem aparecer visualmente no personagem
* Interface simples para trocar aparência

🌍 MUNDO:

* Mapa 2D pequeno e bem organizado (top-down ou lateral)
* Áreas interativas claras:

  * Loja
  * Banco
  * Área de geração de renda
* NPCs simples com falas curtas e úteis (dicas, ambientação)
* Design limpo, sem excesso de informação

💰 SISTEMA IDLE (BALANCEADO):

* Jogador pode ganhar dinheiro clicando ou interagindo
* Sistema automático de geração de renda por segundo
* Progressão moderada (evitar crescimento exagerado ou infinito muito rápido)
* Mostrar claramente:

  * Dinheiro atual
  * Ganho por segundo
* Idle funciona em segundo plano, mas com limites suaves para evitar excesso

📈 PROGRESSÃO:

* Upgrades principais:

  * Melhorar valor do clique
  * Melhorar renda automática
* Crescimento de custo progressivo, porém equilibrado
* Introduzir novos tipos de renda gradualmente
* Evitar inflação extrema de números (manter legibilidade)

🏪 LOJA:

* Interface simples e moderna
* Comprar:

  * Roupas
  * Acessórios
  * Upgrades
* Sistema de desbloqueio progressivo
* Feedback visual claro ao comprar itens

🏆 CONQUISTAS:

* Sistema de conquistas leve e não intrusivo
* Exemplos:

  * Primeira interação
  * Marcos de dinheiro
  * Primeira compra
* Notificações sutis (sem poluir a tela)

💾 SALVAMENTO:

* Salvamento automático com localStorage
* Carregamento automático ao iniciar
* Salvar:

  * Dinheiro
  * Upgrades
  * Itens
  * Aparência
  * Tempo offline

⏳ SISTEMA OFFLINE (SAUDÁVEL):

* Calcular ganhos offline limitados (ex: algumas horas)
* Mostrar resumo ao voltar:

  * Tempo fora
  * Ganho obtido
* Evitar recompensas exageradas

🎨 INTERFACE (UI/UX):

* Interface moderna, minimalista e intuitiva
* HUD limpa com:

  * Dinheiro
  * Ganho por segundo
* Menus simples (loja, conquistas, inventário)
* Foco em clareza e conforto visual
* Adaptado para diferentes tamanhos de tela

🔊 POLIMENTO:

* Animações suaves e discretas
* Feedback visual leve (ex: número subindo ao ganhar dinheiro)
* Partículas simples e elegantes
* Sons opcionais e suaves
* Transições fluidas

🧠 EXPERIÊNCIA DO JOGADOR:

* Evitar mecânicas agressivas ou altamente viciantes
* Não usar loops de recompensa excessivos
* Incentivar exploração e personalização
* Ritmo calmo e agradável (casual game)

🧠 ESTRUTURA DO CÓDIGO:

* Código bem organizado (funções ou módulos)
* Separar lógica, renderização e UI
* Comentários claros
* Fácil de expandir

⚙️ TÉCNICO:

* Rodar em um único arquivo HTML ou estrutura simples
* Preferir JavaScript puro (sem bibliotecas externas)
* Usar requestAnimationFrame para renderização
* Usar deltaTime ou setInterval para sistemas idle
* Código otimizado e legível

🎯 OBJETIVO:
Criar um jogo idle moderno, relaxante e intuitivo, com progressão equilibrada e foco na experiência do jogador, evitando práticas excessivamente viciantes comuns em jogos idle tradicionais.

💻 ENTREGA:

* Código completo e funcional
* Pronto para rodar no navegador
* Interface agradável
* Estrutura clara e organizada
