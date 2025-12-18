
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objetivo

Construa um jogo Hangman (Forca) em linha de comando usando conceitos de manipulação de strings, laços e entrada do usuário. O estudante implementará a lógica do jogo, entrada de letras e condições de vitória/derrota.
 
## 📝 Tarefa

### 🛠️  Hangman Game

#### Description
Implemente um jogo Hangman que seleciona uma palavra aleatória de uma lista, aceita palpites de letras do jogador, atualiza a exibição da palavra em progresso (formato _ _ _), e controla o número de tentativas incorretas restantes.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Accept single-letter guesses and reveal matched letters in the displayed word (ex: _ a _ _ n).
- Track and show the number of incorrect guesses remaining.
- End the game when the word is completamente adivinhada or when attempts run out.
- Display a clear win message on success and a lose message showing the correct word on failure.

#### Example (fluxo simplificado)

```
Palavra: _ a _ _ n
Palpites errados restantes: 4
Digite uma letra: g
Resultado: _ a _ _ n
Palpites errados restantes: 3
```

Mantenha este arquivo como `README.md` dentro da pasta da tarefa e não remova seções obrigatórias do template.
