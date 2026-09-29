# Minecraft
Jogo construir casas
# Nome do Jogo: Minecraft

## 🎯 1. Visão Geral
**Pitch:** Minecraft é um jogo sandbox de sobrevivência e construção onde o jogador explora um mundo infinito gerado procedimentalmente feito de blocos. O objetivo principal é coletar recursos, construir estruturas e sobreviver a ameaças noturnas enquanto explora diferentes dimensões.

---

## ⚒️ 2. Requisitos do Sistema

### ✅ Requisitos Funcionais (RF) - O que o jogo FAZ
1. **RF01:** O jogador deve poder quebrar blocos do cenário e coletar materiais (madeira, pedra, minérios).
2. **RF02:** O sistema deve permitir a fabricação (*crafting*) de ferramentas, armas, armaduras e blocos de construção através de uma grelha $3 \times 3$.
3. **RF03:** O jogo deve salvar o progresso automaticamente ao fechar o mundo ou pausar no menu.
4. **RF04:** O jogador deve poder batalhar contra criaturas hostis (*mobs*) e animais utilizando armas brancas ou de alcance.
5. **RF05:** O jogo deve disponibilizar uma interface de inventário para gerenciamento de itens e barra de acesso rápido (*hotbar*).

### ⚙️ Requisitos Não Funcionais (RNF) - Como o jogo se COMPORTA
1. **RNF01:** O jogo deve carregar novos chunks do mapa em menos de 2 segundos durante a movimentação.
2. **RNF02:** A interface deve ser adaptável para diferentes resoluções (PC, Consoles e Dispositivos Móveis).
3. **RNF03:** O jogo deve rodar a uma taxa mínima de 60 FPS em configurações recomendadas.

---

## 👥 3. Casos de Uso

Atores
- Steven: Ator principal.
- **Servidor/Mundo:** Ator secundário (responsável por gerar o ambiente e controlar mobs).

**Principais Ações (Casos):**
- **UC01 - Jogar Partida:** O Jogador cria ou carrega um mundo e inicia a exploração.
- **UC02 - Criar Item (Crafting):** O Jogador combina materiais na bancada de trabalho para obter um novo item.
- **UC03 - Construir Estrutura:** O Jogador posiciona blocos no cenário para erguer abrigo ou construções.

---

## 🗺️ 4. User Flow (Fluxo de Navegação)

1. **Início** -> Tela de Título / Menu Inicial
2. **Menu Principal** -> Botão "Jogar" -> Seleção de Mundo (ou Criar Novo Mundo)
3. **Gameplay** -> Sobrevivência/Exploração -> Morte do Personagem? -> Tela de "Ressuscitar" ou "Menu Principal"
4. **Gameplay** -> Derrotar o Ender Dragon -> Créditos Finais -> Retorno ao Mundo de Jogo

---

## 🚀 5. Instruções de Entrega
- **Repositório:** `projeto-game-design`
- **Branch:** `docs-inicial`
- **Mensagem de Commit:** `docs: finalizar documentação do jogo`
