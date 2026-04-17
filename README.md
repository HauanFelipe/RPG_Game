# RPG Game

Este projeto é um pequeno jogo de luta em JavaScript, feito para praticar lógica de programação, orientação a objetos e manipulação do DOM. A aplicação coloca dois personagens em combate e atualiza a interface conforme os ataques acontecem.

## Objetivo

O jogo simula uma batalha entre um personagem do jogador e um monstro. Cada lutador possui atributos como vida, ataque e defesa. Ao clicar no botão de ataque, o sistema calcula o dano com um fator aleatório e atualiza a barra de vida na tela.

## Tecnologias usadas

- HTML
- CSS
- JavaScript puro

## Estrutura do projeto

- `index.html`: estrutura da interface do jogo.
- `assets/styles.css`: estilos visuais da página.
- `assets/js/classes.js`: classes dos personagens e regras da batalha.
- `assets/js/script.js`: inicialização da luta e ligação com os elementos da página.

## Conceitos praticados

- Classes e herança com JavaScript
- Encapsulamento com `get` e `set`
- Manipulação do DOM com `querySelector`
- Eventos de clique
- Atualização dinâmica de interface
- Cálculos com valores aleatórios

## Personagens disponíveis

O projeto já possui classes para diferentes tipos de lutadores:

- `Knight`
- `Sorcerer`
- `LittleMonster`
- `BigMonster`

Atualmente, a luta é iniciada com:

- um `Knight` chamado `Hauan`
- um `BigMonster`

## Como executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Clique nos botões de ataque para testar a batalha.

## Como funciona a luta

Quando um ataque acontece:

1. O jogo verifica se algum dos lutadores já está sem vida.
2. Um fator aleatório é aplicado ao ataque e à defesa.
3. O dano é calculado.
4. A vida do personagem atacado é reduzida, se o ataque vencer a defesa.
5. A interface é atualizada com o novo valor de HP e a barra de vida.

## Finalidade do projeto

Este projeto tem foco educacional. Ele é útil para estudar a base do JavaScript em um exemplo visual, simples e fácil de expandir.

## Melhorias futuras

- Exibir mensagens de combate na tela
- Adicionar reinício da batalha
- Permitir escolha de personagens
- Melhorar o layout visual
- Criar sistema de vitória e derrota

## Autor

Projeto desenvolvido para estudo e prática de JavaScript.
