# PROTOTYPE - NOT FOR PRODUCTION
# Question: Can a cozy pixel-art woodland exploration loop lead naturally into an engaging creature battle?
# Date: 2026-11-08

# Clareira de Brasa — protótipo

## Hipótese

Se a pessoa explorar uma clareira aconchegante, encontrar criaturas originais e escolher entre dois movimentos com efeitos diferentes, sentirá curiosidade em continuar conhecendo aquele mundo. O sinal a observar é conseguir encontrar uma criatura, iniciar e concluir uma batalha sem explicações externas em até dois minutos.

## Como executar

Abra `prototype.html` em um navegador moderno. Não há servidor, instalação ou conexão à internet necessários.

- **Explorar:** cena isométrica com visual de MMORPG; setas ou WASD movem nas direções da tela, e no celular segure os controles direcionais.
- **Interagir:** aproxime-se de uma criatura e pressione **E** ou o botão **Interagir**.
- **Mineração:** procure a entrada rochosa na clareira, entre com **E** e pressione **E** perto de um veio; cada mineração rende uma pedra e pode atrair Rocafino, monstro de terra e pedra.
- **Sair da caverna:** aproxime-se da passagem de entrada e pressione **E**. As pedras coletadas ficam no inventário.
- **Pescar:** aproxime-se do lago e pressione **E**; cada fisgada rende um peixe e pode chamar Gelegelo, criatura de água e gelo.
- **Sacudir árvores:** aproxime-se de uma árvore marcada e pressione **E**; cada árvore rende uma maçã e o farfalhar pode atrair Folhibrisa, criatura de planta, voador e inseto.
- **Vender itens:** aproxime-se de Lina na clareira. Use **Vender mochila** para vender todas as pedras (12 moedas cada), peixes (8 moedas cada) e maçãs (5 moedas cada); o saldo aparece no inventário.
- **Batalhar:** escolha um dos dois movimentos; as teclas **1** e **2** também funcionam.
- **Retomar a exploração:** use o botão de retorno após a vitória ou derrota; ele leva de volta à caverna ou à clareira conforme o local do encontro.

## Status

**In-progress** — fatia jogável implementada; ainda não avaliada por jogadores.

## Descobertas até agora

- A demo é independente e funciona localmente, sem baixar recursos.
- A clareira e a caverna usam projeção isométrica, texturas de terreno, água ao redor do bosque, folhagens de outono, detalhes nas construções, iluminação e sombras em pixel art; sprites originais são preservados e renderizados em maior escala.
- A hipótese de diversão e a clareza dos controles ainda precisam de um playtest humano; não há recomendação de produção.
