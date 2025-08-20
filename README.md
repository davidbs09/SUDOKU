# Sudoku Terminal 🔢

Projeto desenvolvido para aprovação no módulo do Bootcamp Santander em parceria com a DIO (Digital Innovation One) - 2025.

## Sobre o Projeto

Este projeto consiste em um jogo de Sudoku totalmente funcional para ser jogado via terminal. O objetivo é proporcionar uma experiência prática de lógica e programação, reforçando conceitos de orientação a objetos, manipulação de coleções, controle de fluxo e interação com o usuário.

O código base foi inspirado no desafio proposto pela DIO, disponível em:
- [Branch master (jogo no terminal)](https://github.com/davidbs09/SUDOKU/tree/master)

> **Atenção:** Este projeto não implementa interface gráfica. Toda a experiência é no terminal, conforme o desafio principal do módulo.

## 🚀 Diferencial da Minha Solução

**Implementação do Sistema de Dicas Inteligente**

Como melhoria ao desafio original, implementei um sistema de dicas integrado ao menu do jogo. Com ele, o usuário pode solicitar até 3 dicas por partida. Cada dica revela a próxima célula (linha e coluna) que está errada ou vazia, mostrando o valor correto para aquela posição. Assim, o jogador pode evoluir no jogo sem perder o desafio de resolver o Sudoku por conta própria!

### Como funcionam as dicas?
- O jogador pode pedir até 3 dicas por partida.
- Cada dica mostra a posição (coluna, linha) e o valor correto para a próxima célula errada ou vazia.
- Após atingir o limite de 3 dicas, não é possível pedir mais dicas até iniciar um novo jogo.
- As dicas nunca mostram valores de células já corretas ou fixas.

## Como Executar

####  Argumentos para passar no running do projeto:
   ```bash
   0,0;4,false 1,0;7,false 2,0;9,true 3,0;5,false 4,0;8,true 5,0;6,true 6,0;2,true 7,0;3,false 8,0;1,false 0,1;1,false 1,1;3,true 2,1;5,false 3,1;4,false 4,1;7,true 5,1;2,false 6,1;8,false 7,1;9,true 8,1;6,true 0,2;2,false 1,2;6,true 2,2;8,false 3,2;9,false 4,2;1,true 5,2;3,false 6,2;7,false 7,2;4,false 8,2;5,true 0,3;5,true 1,3;1,false 2,3;3,true 3,3;7,false 4,3;6,false 5,3;4,false 6,3;9,false 7,3;8,true 8,3;2,false 0,4;8,false 1,4;9,true 2,4;7,false 3,4;1,true 4,4;2,true 5,4;5,true 6,4;3,false 7,4;6,true 8,4;4,false 0,5;6,false 1,5;4,true 2,5;2,false 3,5;3,false 4,5;9,false 5,5;8,false 6,5;1,true 7,5;5,false 8,5;7,true 0,6;7,true 1,6;5,false 2,6;4,false 3,6;2,false 4,6;3,true 5,6;9,false 6,6;6,false 7,6;1,true 8,6;8,false 0,7;9,true 1,7;8,true 2,7;1,false 3,7;6,false 4,7;4,true 5,7;7,false 6,7;5,false 7,7;2,true 8,7;3,false 0,8;3,false 1,8;2,false 2,8;6,true 3,8;8,true 4,8;5,true 5,8;1,false 6,8;4,true 7,8;7,false 8,8;9,false
   ```

## Contato
Projeto desenvolvido por [David Bissaco].

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/david-bissaco-da-silva/) ou confira outros projetos no meu [GitHub](https://github.com/davidbs09).

---

Bootcamp Santander 2025 | DIO - Digital Innovation One
