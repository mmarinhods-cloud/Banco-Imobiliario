# 🎲 Monopoly Web (Banco Imobiliário Clone)

Este é um projeto acadêmico desenvolvido para colocar em prática conceitos de lógica de programação e manipulação de DOM. Trata-se de uma recriação digital do clássico jogo de tabuleiro Monopoly (Banco Imobiliário), rodando inteiramente no navegador.

## 📝 Sobre o Projeto
O foco principal deste projeto foi a construção da "engine" do jogo utilizando JavaScript. O sistema gerencia turnos, economia (compra de propriedades e pagamento de aluguéis), movimentação no tabuleiro e eventos aleatórios, tudo com atualizações dinâmicas na interface do usuário.

## ✨ Funcionalidades
* **Setup Dinâmico:** Suporte para 2 a 4 jogadores, com personalização de nomes e cores.
* **Sistema de Economia:** Compra e venda de propriedades, pagamento de aluguéis e recolhimento de impostos.
* **Tabuleiro Interativo:** Renderização dinâmica das 40 casas do tabuleiro (Propriedades, Sorte/Revés, Prisão, Parada Livre).
* **Animações e Feedback:** Rolagem de dados animada, movimentação visual dos peões casa por casa e um log de ações em tempo real.
* **Regras Específicas:** Sistema de prisão (ficar retido por 3 turnos), falência de jogadores e recebimento de bônus ao passar pelo "Início".

## 🛠️ Tecnologias Utilizadas
* **JavaScript:** Toda a lógica do jogo, gerenciamento de estado e manipulação do DOM.
* **HTML5:** Estrutura da página, modais e formulário de setup.
* **CSS3:** Estilização do tabuleiro, peões, cores dinâmicas de propriedades e layout responsivo.

## 🧠 Aprendizados e Desafios
* **Gerenciamento de Estado:** Utilização de Arrays e Objetos complexos em JavaScript para manter o controle do dinheiro, posição e propriedades de cada jogador de forma independente.
* **Event Loop e Timers:** Uso de `setInterval` e `setTimeout` para criar as animações de rolagem de dados e o movimento suave dos peões no tabuleiro.
* **Separação de Preocupações:** Organização de funções específicas para renderização (`renderBoard`, `renderPlayers`) e regras de negócio (`handleSpace`, `buyProperty`).

## 🚀 Como Executar
Por ser uma aplicação 100% Front-end (Client-side), não é necessária a instalação de nenhum servidor ou dependência.

1. Faça o clone do repositório:
   `git clone https://github.com/SeuUtilizador/SeuRepositorio.git`
2. Abra a pasta do projeto.
3. Dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador favorito.
4. Adicione os jogadores e comece a jogar!
