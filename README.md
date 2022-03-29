# Lotecaria
Simulador de loteria

Um simulador de loteria onde o usuário escolhe 6 números e o
programa sorteia 6 números e verifica a quantidade de acertos.

## Tecnologias utilizadas
- **HTML:** Estrutura do site
- **CSS:** Estilos do site
- **JS:** Funções do site
- ~~BootStrap~~: Não foi utilizado

### Melhorias Possíveis

1. [x] Subir no github pages
2. [ ] Trocar o Alert por mensagens mais amigaveis
3. [ ] Realizar teste para descobrir bugs 🦟

#### Disponivel em:
[GitHubPages](https://hemanuela-fernandes.github.io/Lotecaria/)

### Código principal

```js:
function verificaAcertos() {
    let cont = 0
    numDig.forEach(function (valor, index) {
        if (numSort.includes(valor)) {
            cont = cont + 1
        }
    })
    document.getElementById("total").innerText = cont
}

```

### Prints da tela do WebApp:

| tela inicial | Primeira rodada |
| ------------ | --------------- |
|   imagem 1   |   imagem 2      |
