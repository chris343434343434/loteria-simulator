# projeto loteria-simulator
trabalho  topicos especiais tecnologia e infomação simulador de loteria.
Onde o usuario escolhe 6 numeros e o programa sorteia outros 6 numeros,
e apos isso verifica a quantidade de acertos.
## tecnologias utilizadas 
- **HTML:** _Estrutura do site._ 
- **CSS:** *estilo do site.*
- **JS:** *funções do site.*
- ~~~BootStrap~~: *Não foi utilizado.*


### Melhorias Possiveis.
1. [x] Subir no github pages 
2. [ ] Trocar o Alert por mensagens mais amigaveis.
3. [ ] Realizar teste para descobrir bugs.

### disponivel em:
[GitHubPages](https://chris343434343434.github.io/loteria-simulator/)


### ScreenShots

| Tela inicial | Primeiro teste | 
|--------------|----------------|
|---imagen 1---|----imagen 2----|
|--PeloFolder--|----------------|
|![img1](/img/img1.png)|![img2](/img/img2.png)|
|---porLink----|----------------|
|![img1](https://raw.githubusercontent.com/chris343434343434/loteria-simulator/master/img/img1.png)|![img2](https://raw.githubusercontent.com/chris343434343434/loteria-simulator/master/img/img2.png)|

### Codigo
```js:
function sorteioNum() {
        numSort = []
        do {
                let sort = Math.ceil(Math.random() * 60)
                if (!numSort.includes(sort)) {
                        numSort.push(sort)
                }
        } while (numSort.length < 6);
        console.log(numSort)
}
```