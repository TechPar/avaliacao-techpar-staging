# avaliacao-techpar-staging

Este material tem tanto caráter de avaliação quanto de apresentação da stack
de trabalho da techpar.

O prazo de realização dos desafios é de uma semana e a forma de entrega é
fazendo um fork deste repositório do github e enviando o link da solução (i.e.
o link para o seu fork) nas issues deste repositório:

[Link das issues](https://github.com/TechPar/avaliacao-techpar-staging/issues)

Qualquer dúvida adicional, use o espaço de issues do projeto para perguntar.
Pode perguntar qualquer coisa, este teste é assistido

## Dos desafios

Cada desafio consiste em uma realidade de trabalho da Techpar. O candidato
deverá adicionar ao repositório _forkado_ uma pasta correspondente à solução de
cada um dos desafios. Eles tem complexidade crescente, e a ideia é que cada
candidato use de todas as habilidades de investigação, aprendizado e, não menos
importante, **javascript** para prover solução ao que é pedido.

### Desafio_1

**Objetivo:** Demonstrar ser capaz de criar um projeto javascript gerenciado
pelo NPM e ter entendimento básico do funcionamento dos módulos. Adicionalmente
este desafio coloca em teste as habilidades do candidato em usar o git/github.

Crie um projeto javascript que consista em dois scripts:

- index.js
- reverse.js

O index.js é o ponto de entrada e deverá receber uma palavra e devolvê-la
revertida. Exemplo:

```bash
node index.js olá
álo
```

O reverse.js deverá exportar a função que inverte a string. o index deverá dar
**require** nesta função.

Adicione no repositório uma pasta chamada **desafio_1** e dentro dela deve ter
os dois scripts e, opcionalmente, o **package.json**, que é criado após usar o
comando **npm init**.

### Desafio_2

**Objetivo:** Demonstrar ser capaz de usar uma biblioteca importada do registro
do npm.

Crie um projeto javascript que devolva o md5 da string informada. Exemplo:

```bash
node index.js olá
ab11fa17ff3337a200cb2714dbc2318c
```

O projeto deve ter, no mínimo, os seguintes arquivos:

- index.js
- package.json

### Desafio_3

**Objetivo:** Demonstrar capacidade de consumir uma api REST, bem como estudar
e avaliar respostas em JSON para descobrir a melhor forma de
consumo/apresentação dos dados oferecidos

O github tem uma api pública que pode ser consumida anonimamente:

[https://developer.github.com/v3/](https://developer.github.com/v3/)

O axios é um cliente HTTP para consumir API's rest disponível no registro
do npm:

[https://github.com/axios/axios](https://github.com/axios/axios)

Faça um projeto npm para mostrar o número de issues do projeto de avaliação.
Exemplo:

```bash
node index.js https://api.github.com/repos/techpar/avaliacao-techpar-staging
1 issue(s)
```

O projeto deve ter, no mínimo, os seguintes arquivos:

- index.js
- package.json

## Observações

Os exercícios são básicos, procuram mais fomentar a autonomia na pesquisa de
soluções na internet, vídeos, outros projetos e pessoas.

Atente para o objetivo de cada desafio, bem como os exemplos de uso oferecidos.
O uso de linha de comando é essencial nos três porque será parte do dia a dia
na techpar.

Após a entrega do desafio, teremos uma entrevista final na sede da techpar.

A data de contagem para a semana de prazo começa na data da criação do fork
deste projeto no github.

Bons estudos!
