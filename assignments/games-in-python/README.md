# 📘 Assignment: Games in Python

## 🎯 Objective

Construir dois mini jogos (Adivinhação de Número e Hangman) para praticar uso de loops, condicionais, funções e manipulação de entrada do usuário.

## 📝 Tasks

### 🛠️ Adivinhação de Número

#### Description
Implemente um jogo onde o programa escolhe um número secreto dentro de um intervalo e o jogador tenta adivinhar com feedback (maior/menor) até acertar ou acabar as tentativas.

#### Requirements
Completed program should:

- Escolher aleatoriamente um número dentro de um intervalo (ex.: 1–100)
- Limitar tentativas (ex.: 7) e mostrar quantas restam
- Informar se o palpite é maior ou menor que o número secreto
- Validar entradas: numérico e dentro do intervalo
- Impedir contagem de tentativas em entrada inválida
- Exibir mensagem de vitória com número de tentativas usadas ou derrota mostrando o número secreto
- Organizar lógica em funções (ex.: jogar(), obter_palpite())

### 🛠️ Hangman (Forca)

#### Description
Crie uma versão simples do jogo da forca onde o jogador tenta descobrir a palavra secreta letra por letra antes de esgotar as tentativas.

#### Requirements
Completed program should:

- Ter uma lista de palavras e escolher uma aleatoriamente
- Mostrar progresso da palavra em formato com sublinhados (ex.: _ _ a _)
- Controlar letras já tentadas e impedir repetição
- Reduzir tentativas apenas em erros (ex.: 6 tentativas iniciais)
- Validar entrada: uma única letra alfabética
- Exibir vitória ao revelar todas as letras ou derrota mostrando a palavra completa
- Usar funções para separar responsabilidades (ex.: escolher_palavra(), exibir_estado(), jogar_forca())
