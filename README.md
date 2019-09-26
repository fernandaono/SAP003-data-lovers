# Projeto Data Lovers
## Pokémon

## Índice

* [1. Introdução](#1-introdução)
* [2. Definição de produto](#2-definição-de-produto)
* [3. Histórias de usuário](#3-histórias-de-usuário)
* [4. Protótipo de baixa fidelidade](#-protótipo-de-baixa-fidelidade)

***

## 1. Introdução

O projeto Data Lovers é o segundo projeto proposto no bootcamp da Laboratória e baseia-se na criação de um produto (dashboard) a partir de uma base de dados. A base de dados escolhida foi do jogo Pokémon GO, em que há uma lista com os 151 Pokémons da região de Kanto, com suas respectivas estatísticas utilizadas no jogo.

## 2. Definição de produto

## 3. Histórias de usuário

## 4. Protótipo de baixa fidelidade

<!-- # Data Lovers

## Índice

* [1. Preâmbulo](#1-preâmbulo)
* [2. Resumo do projeto](#2-resumo-do-projeto)
* [3. Objetivos de aprendizagem](#3-objetivos-de-aprendizagem)
* [4. Considerações gerais](#4-consideracoes-gerais)
* [5. Critérios mínimos de aceitação do projeto](#5-criterios-minimos-de-aceitacao-do-projeto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Considerações técnicas](#7-considerações-técnicas)
* [8. Pistas, dicas e leituras complementares](#8-pistas-dicas-e-leituras-complementares)
* [9. Checklist](#9-checklist)

***

## 1. Preâmbulo

Segundo a [Forbes](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read)
90% dos dados que existem hoje foram gerados durante os últimos dois anos.
A cada dia geramos 2.5 milhões de terabytes de dados, uma cifra sem
precedentes.

Apesar disso, os dados por si só são de pouca utilidade. Para que essas grandes
quantidades de dados se convertam em **informação** compreensível para os
usuários, precisamos entender e processar estes dados. Uma forma simples de
fazer isso é criando _interfaces_ e _visualizações_.

Na imagem seguinte, você pode ser como os dados que estão na parte esquerda
podem ser usados para construir a interface amigável e compreensível que está
na parte direita.

![json-interface](https://lh4.googleusercontent.com/Tn-RPXS26pVvOTdUzRT1KVaJ-_QbFs9SpcGLxSPE43fgbHaXtFgMUInuDt7kV41DkT1j8Tt29V0LxQW7SMtC6digOIhfTXSBKdwI08wUwhD3RAqlwy0hjfmhZ2BFe91mtmCSEqysfgk)

\* Você pode ver em detalhe os dados neste [link](https://gist.github.com/lalogf/dd4aa3017a9f8aa8f90dfbca382c4dc9#file-student-json)
e a interface construída a partir dele neste [link](https://app.talento.laboratoria.la/profile/HFOoMpOreBU2psCcjjLg5O2EWEv2).

## 2. Resumo do projeto

Neste projeto você **construirá uma _página web_ para visualizar um conjunto
(set) de dados_** que se adeque às necessidades de seu usuário.

Como entregável final terá uma página web que permita **visualizar dados,
filtrá-los, ordená-los e fazer algum cálculo agregado**. Por cálculo agregado
nos referimos aos diversos cálculos que pode fazer com os dados para mostrar a
informação mais relevante para os usuários (médias, valores máximos e míimos,
etc).

Para este projeto trazemos uma série de dados de _temáticas diferentes_ para
que você explore e decida com qual delas deseja trabalhar. Escolhemos
especificamente estes conjuntos de dados porque cremos que se adequem bem a
esta etapa de sua aprendizagem.

Uma vez que você defina sua área de interesse, busque entender quem é seu
usuário e o que exatamente ele necessita saber ou ver, para que assim possa
construir a interface que o ajude a interagir e entender melhor os dados.

Este são os dados que propomos:

* [Indicadores de desenvolvimento do Banco Mundial](src/data/worldbank/worldbank.json)
  de alguns países (Brasil, Chile, México e Perú). Estes dados incluem
  indicadores demográficos, econômicos e comerciais.
* [Pokémon](src/data/pokemon/pokemon.json):
  Neste conjunto você encontrará uma lista com os 151 Pokémon da região de
  Kanto, com suas respectivas estatísticas utilizadas no jogo [Pokémon GO](http://pokemongolive.com).
* [Steam notícias](src/data/steam/steam.json):
  Lista notícias relacionadas aos jogos da plataforma [Steam](https://store.steampowered.com/).
* [League of Legends - Challenger leaderboard](src/data/lol/lol.json):
  Este conjunto mostra a lista de jogadores de uma liga do jogo League of
  Legends (LoL). Você pode revisar a documentação da API neste [link](https://developer.riotgames.com/api-methods/).
* [Pessoas feridas por meios de transporte nos EUA](src/data/injuries/injuries.json).
  Este conjunto mostra o número de pessoas feridas em acidentes de transporte,
  com dados anuais desde 1960 e categorizados por tipo de transporte
  (avião, barco, automóvel, moto e bicicleta).
* [Rick and Morty](src/data/rickandmorty/rickandmorty.json).
  Lista de personagens da série Rick & Morty. Você pode revisar a documentação
  da API neste [link](https://rickandmortyapi.com).
* [Pacientes nos EUA](src/data/patient/patient.json).
  Uma lista de pacientes nos EUA. Você pode revisar a documentação da API neste
  [link](https://r2.smarthealthit.org/Patient).

Alguns conjuntos de dados têm uma identidade gráfica que você deverá utilizar
na interface. Os guias de identidade gráfica podem ser encontrados neste
[link](https://drive.google.com/open?id=1eeWFqrWpy-OYOH4EHDckFGunyrm9iNeE).

## 3. Objetivos de aprendizagem

O objetivo principal deste projeto é que aprenda a desenhar e construir uma
interface web onde se possa visualizar e manipular dados, entendendo o que o
usuário necessita.

Em outras palavras, você aprenderá a:

* Aplicar e aprofundar tudo o que aprendeu no projeto anterior.
* Pensar nas **necessidades dos usuários** para criar histórias de usuário.
* Escrever e trabalhar com **histórias de usuário**, suas definições de pronto
  (_definition of done_) e critérios de aceitação como ferramentas centrais
  de organização e planejamento de seu trabalho.
* Definir que dados utilizar e de que forma exibí-los em seu produto,
  baseando-se no seu **entendimento do usuário**.
* Iterar o desenho do produto, baseando-se nos resultados dos
  **testes de usabilidade**.
* Manipular **arrays e objetos**.
* **Manipular o DOM** (agregar elementos de forma dinâmica)
* **Manejar eventos do DOM** para permitir interação com o usuário (filtros,
  ordenação, etc).
* Entender os benefícios e complexidades de **trabalhar em equipe** em um
  ambiente de incerteza.

## 4. Considerações gerais

* Este projeto será executado em duplas.
* Este projeto será entregue através do GitHub e a interface deve ser publicada
  no [GitHub Pages](https://pages.github.com/).
* Tempo para completá-lo: três semanas.

## 5. Critérios mínimos de aceitação do projeto

Os critérios considerados para que tenha terminado este projeto são:

### Definição de produto

Documente brevemente seu trabalho no arquivo `README.md` de seu repositório,
contando como foi o processo de desenho e como você acredita que o produto
possa resolver o problema (ou problemas) de seu usuário.

### Histórias de usuário

Uma vez que entenda a necessidade dos usuários, escreva as [Historias de
Usuario](https://es.wikipedia.org/wiki/Historias_de_usuario) que representem
tudo que o usuário precisa fazer/ver. As **histórias de usuário** devem ser o
resultado de seu processo de investigação/pesquisa de seus usuários.

Não esqueça de incluir a definição de pronto (_definition of done_) e os
critérios de aceitação para cada uma.

Na medida do possível, termine uma história de usuário antes de passar para a
seguinte (cumpra com as definições de pronto + critérios de aceitação).

### Desenho de interface do usuário

#### Protótipo de baixa fidelidade

Durante seu trabalho você deverá fazer e iterar rascunhos de sua solução usando
lápis e papel. Recomendamos que fotografe todas as iterações que fizer, suba
para seu repositório e as mencione no `README.md`.

#### Testes de usabilidade

Durante o desafio você deverá fazer testes de usabilidade com usuários
diferentes, e com base nos resultados desses testes, iterar seus desenhos de
interface. Conte-nos quais problemas de usabilidade você detectou através dos
testes e como os resolveu na proposta final.

### Implementação da interface de usuário (HTML/CSS/JS)

Após desenhar sua interface de usuário, deverá trabalhar na sua implementação.
**Não** é necessário que construa a interface exatamente da mesma forma que
desenhou. Terá um tempo limitado para trabalhar no projeto, então você deve
priorizar as tarefas.

No mínimo, sua implementação deverá:

1. Mostrar os dados em uma interface: pode ser em cards, tabelas, listas, etc.
2. Permitir ao usuário filtrar e ordenar dados;
3. Calcular estatísticas, como média aritmética, máximo ou mínimo de algum
   atributo numérico, ou contar quantas vezes aparece determinada informação,
   por exemplo.
4. Ser _responsivo_, ou seja, deve ser visualizada sem problemas a partir de
   diversos tamanhos de tela: celulares, tablets, notebooks, etc.

### Testes unitários

O _boilerplate_ do projeto não inclui testes unitários. Assim, você terá que
escrever seus próprios testes para as funções encarregadas de _processar_,
_filtrar_ e _ordenar_ os dados, assim como _calcular_ estatísticas.

Seus testes unitários devem ter cobertura mínima de 70% de _statements_
(_sentenças_), _functions_ (_funções_), _lines_ (_linhas_), e _branches_
(_ramos_) do arquivo `src/data.js`, que irá conter suas funções e que está
detalhado na seção de [Considerações técnicas](#srcdatajs).

## 6. Hacker edition

As seções chamadas _Hacker Edition_ são **opcionais**. Se já tiver terminado
todos os requisitos anteriores e tiver tempo, pode tentar completá-las. Dessa
forma, você pode aprofundar e/ou exercitar mais os objetivos de aprendizagem
deste projeto.

Features/características extra sugeridas:

* Ao invés de consumir dados estáticos do repositório, pode fazer isso de forma
  dinâmica, carregando um arquivo JSON com `fetch`. A pasta `src/data` contém
  uma versão `.js` e uma `.json` de cada conjunto de dados.
* Adicione à sua interface visualização de dados em forma de gráficos. Para
  isso, recomendamos explorar bibliotecas de gráficos como [Chart.js](https://www.chartjs.org/)
  ou [Google Charts](https://developers.google.com/chart/).
* 100% de cobertura nos testes.

## 7. Considerações técnicas

A lógica do projeto deve estar implementada somente em JavaScript (ES6), HTML e
CSS. Neste projeto não está permitido o uso de bibliotecas e frameworks, apenas
[vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e),
com exceção das bibliotecas para gráficos (ver
[_Parte opcional_](#6-hacker-edition) acima).

Não se deve utilizar a _pseudo-variável_ `this`.

O _boilerplate_ contém uma estrutura de arquivos como ponto de partida, assim
como toda a configuração de dependências:

```text
.
├── EXTRA.md
├── README.md
├── package.json
├── src
|  ├── data
|  |  ├── injuries
|  |  |  ├── injuries.js
|  |  |  └── injuries.json
|  |  ├── lol
|  |  |  ├── lol.js
|  |  |  └── lol.json
|  |  ├── patient
|  |  |  ├── patient.js
|  |  |  └── patient.json
|  |  ├── pokemon
|  |  |  ├── pokemon.js
|  |  |  └── pokemon.json
|  |  ├── rickandmorty
|  |  |  ├── rickandmorty.js
|  |  |  └── rickandmorty.json
|  |  ├── steam
|  |  |  ├── steam.js
|  |  |  └── steam.json
|  |  └── worldbank
|  |     ├── worldbank.js
|  |     └── worldbank.json
|  ├── data.js
|  ├── index.html
|  ├── main.js
|  └── style.css
└── test
   └── data.spec.js

directory: 10 file: 22
```

### `src/index.html`

Como no projeto anterior, existe um arquivo `index.html`. Como já sabe, aqui
entra a página que vai ser exibida ao usuário. Também serve para indicar quais
scripts serão utilizados e juntar tudo o que foi feito.

Neste arquivo você encontrará uma séris de _tags_ `<script>` _comentadas_. Para
carregar diferentes fontes de dados, você deverá "descomentar" estas _tags_.
Cada um destes scripts criará uma variável global com os dados correspondentes
à fonte escolhida.

Por exemplo, se "descomentamos" a seguinte linha:

```html
<!-- <script src="./data/worldbank/worldbank.js"></script> -->
```

A linha ficaria assim:

```html
<script src="./data/worldbank/worldbank.js"></script>
```

E agora teríamos a variável global `WORLDBANK` disponível em nossos outros
scripts (como `src/data.js` ou `src/main.js`).

### `src/main.js`

Recomendamos que utilize `src/main.js` para todos os códigos que tenham a ver
com a exibição dos dados na tela. Com isto nos referimos basicamente à
interação com o DOM. Operações como criação de nós, registro de manejadores de
eventos (_event listeners_ ou _event handlers_) e etc.

Esta não é a única forma de dividir seu código. Pode utilizar mais arquivos e
pastas, sempre e quando a estrutura estiver clara para suas colegas.

### `src/data.js`

O coração deste projeto é a manipulação de dados através de arrays e objetos.

Recomendamos que este arquivo contenha toda a funcionalidade que corresponda a
obter, processar e manipular dados (suas funções):

* `filterData(data, condition)`: esta função receberia os dados e nos
  retornaria os que cumprem com a condição.

* `sortData(data, sortBy, sortOrder)`: esta função recebe três parâmetros.
  O primeiro, `data`, nos entrega os dados.
  O segundo, `sortBy`, diz respeito a qual das informações quer usar para
  ordenar.
  O terceiro, `sortOrder`, indica se quer ordenar de maneira crescente ou
  decrescente.

* `computeStats(data)`: essa função nos permite fazer cálculos estatísticos
  básicos para serem exibidos de acordo com o que os dados permitem.

Estes nomes de funções e parâmetros são somente referência, o que vocês decidir
utilizar vai depender da sua implementação.

Estas funções devem ser [_puras_](https://imasters.com.br/desenvolvimento/serie-js-e-vida-pure-functions-funcoes-puras)
e independentes do DOM. Estas funções serão depois usadas a partir do arquivo
`src/main.js`, ao carregar a página e a cada vez que o usuário interagir com
a interface (cliques, seleções, filtros, ordenação, etc).

### `src/data`

Nesta pasta estão os dados de diferentes fontes. Você vai encontrar uma pasta
para cada fonte, e dentro de cada pasta estão dois arquivos: um com a extensão
`.js` e outro `.json`. Ambos os arquivos contém os mesmos dados; a diferença é
que podemos usar o `.js` com uma tag `<script>`, enquanto o `.json` servirá
para, opcionalmnente, ser carregado de forma assíncrona com
[`fetch()`](https://developer.mozilla.org/pt-br/docs/Web/API/Fetch_API)
(ver seção da [_Parte Opcional_](#6-hacker-edition)).

### `test/data.spec.js`

Você também deverá fazer os teste unitários das funções implementadas no
arquivo `data.js`.

***

## 8. Pistas, dicas e leituras complementares

### Primeiros passos

Antes de começar a escrever o código, você deve definir seu produto com base no
conhecimento que puder obter a respeito de seus usuários. Estas perguntas podem
ajudar:

* Quem são os usuários principais do produto?
* Quais são os objetivos dos usuários com relação ao produto?
* Quais são os dados mais relevantes que querem ver na interface e por quê?
* Quando utilizam ou utilizariam o produto?
* Toda sua investigação prévia deve ter como resultado as histórias de
  usuário de seu projeto.

Quando estiver pronta para codar, sugerimos começar desta forma:

1. Uma das integrantes da dupla deve fazer um :fork_and_knife:
   [fork](https://help.github.com/articles/fork-a-repo/) do repositório de sua
   turma (a equipe de formação fornecerá o link). A outra integrante da dupla
   deve fazer um fork **a partir do repositório de sua companheira** e
   [configurar](https://gist.github.com/BCasal/026e4c7f5c71418485c1) um
   `remote` a partir dele.

2. :arrow_down: [Clona](https://help.github.com/articles/cloning-a-repository/)
   seu _fork_ para seu computador (cópia local).

3. Instale as dependências do projeto com o comando `npm install`, assumindo
   que já tenha instalado o [Node.js](https://nodejs.org/) (que inclui [npm](https://docs.npmjs.com/)).

4. Se tudo correr bem, deve ser capaz de executar os :traffic_light:
   testes unitários (unit tests) com o comando `npm test`.

5. Para ver a interface de seu programa no navegador, utilize o comando
   `npm start` para subir o servidor web no endereço `http://localhost:5000`.

6. Comece a codar! :rocket:

***

### Conteúdo de referência

#### UX Design (Experiência do usuário)

* Pesquisa com usuarios / entrevistas
* Princípios de design/UI

#### Desenvolvimento Front-End

* Unidade de testes do curso de JavaScript do LMS.
* Unidade de arrays do curso de JavaScript do LMS.
* Unidade de objetos do curso de JavaScript do LMS.
* Unidade de funções do curso de JavaScript do LMS.
* Unidade de DOM do curso de JavaScript do LMS.
* [Array no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array)
* [Array.sort no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
* [Array.map no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [Array.filter no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/filtro)
* [Array.reduce no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
* [Array.forEach no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
* [Object.keys no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
* [Object.entries no MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)
* [Fetch API no MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
* [json.org](https://json.org/json-pt.html)

#### Ferramentas

* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)
* [Node.js](https://nodejs.org/)
* [Jest](https://jestjs.io/)

#### Organização do trabalho

* [Histórias de Usuário](https://www.youtube.com/watch?v=sEtiCJfXTE8)
* [Definição de pronto](https://www.youtube.com/watch?v=Kfss63Q42F8)
* [Critérios de aceitação](https://medium.com/@karladiasn/user-stories-e-crit%C3%A9rios-de-aceita%C3%A7%C3%A3o-317c48403fcd)
* [Guia para Data Lovers](https://docs.google.com/presentation/d/1bOq8ns5wsvXdksdqYL3aQoxzFQsXTVlyvlV-yxI2oBM/present?token=AC4w5VhHBbEEA9u2w8bm3Ey1Cse349frbg%3A1567540902700&includes_info_params=1&eisi=CM_ytPW4teQCFQrJgQodeTcEZg#slide=id.g5282e1a53f_1_106)

***

## 9. Checklist

* [ ] Usar VanillaJS.
* [ ] Não utilizar `this`.
* [ ] Passa pelo linter (`npm run pretest`)
* [ ] Passa pelos testes (`npm test`)
* [ ] Testes unitários cobrem um mínimo de 70% de statements, functions,
  lines e branches.
* [ ] Inclui uma _definição de produto_ clara e informativa no `README.md`.
* [ ] Inclui histórias de usuário no `README.md`.
* [ ] Inclui rascunho da solução (protótipo de baixa fidelidade) no
  `README.md`.
* [ ] Inclui uma lista de problemas detectados nos testes de usabilidade no `README.md`.
* [ ] UI: Mostra lista/tabela/etc com dados e/ou indicadores.
* [ ] UI: Permite ordenar dados por um ou mais campos (asc e desc).
* [ ] UI: Permite filtrar dados com base em uma condição.
* [ ] UI: É _responsivo_. -->
