# PROTOTYPE - NOT FOR PRODUCTION
# Question: Can a cozy pixel-art woodland exploration loop lead naturally into an engaging creature battle?
# Date: 2026-11-08

# Clareira de Brasa — Crônicas da Semente-Lume

## Hipótese

Se a pessoa explorar regiões com identidade própria, descobrir moradores diferentes em cada habitat e registrar encontros no caderno, sentirá vontade de conhecer todo o bosque. O sinal a observar é encontrar mais de uma espécie, vencer uma batalha e entender o progresso de descobertas sem explicações externas.

## Como executar

Abra `prototype.html` em um navegador moderno. Não há servidor, instalação ou conexão à internet necessários.

- **Explorar:** cena isométrica com visual de MMORPG; setas ou WASD movem nas direções da tela, e no celular segure os controles direcionais.
- **Interagir:** aproxime-se de uma criatura e pressione **E** ou o botão **Interagir**.
- **Mineração:** siga para o lado leste da clareira, entre na gruta pela passagem rochosa e pressione **E** perto de um veio; cada mineração rende uma pedra e os encontros da gruta podem revelar Rocafino ou Quartilume.
- **Sair da caverna:** aproxime-se da passagem de entrada e pressione **E**. As pedras coletadas ficam no inventário.
- **Pescar:** o lago fica no lado oeste da clareira, separado da entrada da mina. Aproxime-se da margem e pressione **E**; após a animação, cada fisgada rende um peixe e pode chamar uma criatura de maré.
- **Sacudir árvores:** aproxime-se de uma árvore marcada e pressione **E**; cada árvore rende uma maçã e o farfalhar pode atrair criaturas do bosque.
- **Vender itens:** aproxime-se de Lina na clareira. Use **Vender mochila** para vender todas as pedras (12 moedas cada), peixes (8 moedas cada) e maçãs (5 moedas cada); o saldo aparece no inventário.
- **Batalhar:** escolha Folha Veloz, Sopro de Brasa ou Dardo de Orvalho; as teclas **1**, **2** e **3** também funcionam. Os elementos alteram o dano, incluindo a fraqueza de Pedra contra Maré e Broto.
- **Encontrar criaturas:** moradores aparecem em pontos de encontro diferentes conforme o habitat — pomar, trilhas, lago e gruta. Ao vencer um encontro, o ponto fica quieto por alguns segundos antes de receber outro morador.
- **Caderno da Semente-Lume:** cada espécie encontrada entra nas descobertas da expedição; registre os oito moradores e ganhe uma semente-lume ao vencer encontros no bosque.
- **Retomar a exploração:** use o botão de retorno após a vitória ou derrota; ele leva de volta à caverna ou à clareira conforme o local do encontro.

## Status

**In-progress** — fatia jogável com spawns por habitat; ainda não avaliada por jogadores.

## Descobertas até agora

- A demo é independente e funciona localmente, sem baixar recursos.
- A clareira e a caverna usam projeção isométrica, texturas de terreno, água ao redor do bosque, folhagens de outono, detalhes nas construções, iluminação e sombras em pixel art; sprites originais são preservados e renderizados em maior escala.
- O bosque apresenta regiões com nomes e pistas próprias; os pontos de encontro sorteiam criaturas adequadas ao local e reaparecem após uma breve pausa.
- O caderno registra até oito espécies; conhecer um morador atualiza as descobertas e vencer o encontro rende uma semente-lume.
- A hipótese de diversão e a clareza dos controles ainda precisam de um playtest humano; não há recomendação de produção.
