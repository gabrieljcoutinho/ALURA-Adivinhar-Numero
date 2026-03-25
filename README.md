# 🎯 Jogo de Adivinhação com JavaScript

Este projeto simula um jogo onde o programa tenta adivinhar um número secreto gerando números aleatórios até acertar.

---

## 💻 Código

```javascript
const numeroSecreto = 8
let numeroAleatorio = 0;
let tentativas = 0;

while (numeroSecreto !== numeroAleatorio){
    numeroAleatorio = Math.floor(Math.random() * (50 - 1 + 1) + 1);
    tentativas++;
}

console.log(`adivinhou em ${tentativas} tentativas`)
