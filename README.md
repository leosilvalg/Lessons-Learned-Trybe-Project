### Termos e acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

# Boas vindas ao repositório do projeto Lições Aprendidas!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Atenção a cada passo e, se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

---

## SUMÁRIO

- [Habilidades](#habilidades)
- [Entregáveis](#entregáveis)
  - [O que deverá ser desenvolvido](#o-que-deverá-ser-desenvolvido)
  - [Desenvolvimento](#desenvolvimento)
  - [Data de entrega](#data-de-entrega)
- [Instruções para entregar seu projeto](#instruções-para-entregar-seu-projeto)
  - [Antes de começar a desenvolver](#antes-de-começar-a-desenvolver)
  - [Durante o desenvolvimento](#durante-o-desenvolvimento)
- [Como desenvolver](#como-desenvolver)
  - [Linter](#linter)
  - [Avaliador Automático](#avaliador-automático)
- [Requisitos](#requisitos)
  - [Dicas](#dicas)
  - [Lista de requisitos](#lista-de-requisitos)
    - [1. Adicione uma cor de fundo específica para a página](#1-adicione-uma-cor-de-fundo-específica-para-a-página)
    - [2. Adicione uma barra superior com um título](#2-adicione-uma-barra-superior-com-um-título)
    - [3. Adicione uma foto sua à página](#3-adicione-uma-foto-sua-à-página)
    - [4. Adicione uma lista de lições aprendidas à página](#4-adicione-uma-lista-de-lições-aprendidas-à-página)
    - [5. Crie uma lista de lições que ainda deseja aprender para a página](#5-crie-uma-lista-de-lições-que-ainda-deseja-aprender-para-a-página)
    - [6. Adicione um rodapé para a página](#6-adicione-um-rodapé-para-a-página)
    - [7. Insira pelo menos um link externo na página](#7-insira-pelo-menos-um-link-externo-na-página)
    - [8. Crie um artigo sobre seu aprendizado](#8-crie-um-artigo-sobre-seu-aprendizado)
    - [9. Crie uma seção que conta uma passagem sobre seu aprendizado](#9-crie-uma-seção-que-conta-uma-passagem-sobre-seu-aprendizado)
    - [10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles](#10-aplique-elementos-html-de-acordo-com-o-sentido-e-propósito-de-cada-um-deles)
  - [Bônus](#bônus)
    - [11. Teste a semântica da sua página está aprovada pelo site CodeSniffer](#11-teste-a-semântica-da-sua-página-está-aprovada-pelo-site-codesniffer)
    - [12. Adicione uma tabela à página](#12-adicione-uma-tabela-à-página)
    - [13. Utilize o Box model](#13-utilize-o-box-model)
    - [14. Altere atributos relacionados as fontes](#14-altere-atributos-relacionados-as-fontes)
    - [15. Posicione o seu artigo e a seção sobre aprendizados um ao lado do outro](#15-posicione-o-seu-artigo-e-a-seção-sobre-aprendizados-um-ao-lado-do-outro)
- [Depois de terminar o desenvolvimento](#depois-de-terminar-o-desenvolvimento)
- [Revisando um pull request](#revisando-um-pull-request)
- [Avisos Finais](#avisos-finais)


## Habilidades

Neste projeto, você será capaz de:

* Utilizar _HTML_ para construir páginas WEB.
* Utilizar _HTML_ semântico para tornar sua página mais acessível e melhor ranqueada.
* Utilizar _CSS_ para adicionar estilo e posicionar elementos.

---

## O que deverá ser desenvolvido

Você vai desenvolver um site que contenha uma série de informações sobre o que você aprendeu aqui na Trybe ao longo dos últimos três blocos. Seu site deverá estar com elementos posicionados e estilizados e além disto, deverá conter semântica apropriada para que seja acessível e melhor ranqueado.

💡Veja o exemplo a seguir de como o projeto pode se parecer depois de pronto. Lembre-se que você pode ~~e deve~~ ir além para deixar o projeto com a sua cara e impressionar todas as pessoas!

![exemplo](./exemplo.png)

## Desenvolvimento

Você deve desenvolver uma página HTML estilizada com CSS.

Através desta aplicação, será possível realizar a construção de código HTML, posicionamento e estilização CSS.

---

### 👀Observações importantes:

* Lembrem-se que como pessoas desenvolvedoras devemos fazer pesquisas e garimpar resultados para auxiliar no entendimento do assunto. Assim, para solucionar os requisitos do projeto é inevitável e estimulado que pesquisas sejam feitas nas mais variadas fontes (course, vídeos do course, google, youtube, etc) sempre tomando cuidado para utilizar fontes "confiáveis" nas pesquisas da Internet, como por exemplo:
  
  * [Javascript.com](http://javascript.com/)
  
  * [W3Schools](https://www.w3schools.com/js/default.asp)
  
  * [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  
  * [StackOverflow](https://pt.stackoverflow.com/questions/tagged/javascript)
  

### 1. Adicione uma cor de fundo específica para a página

Possuir cor de fundo: rgb(253, 251, 251)

**O que será verificado:**

- Possuir cor de fundo: rgb(253, 251, 251)

### 2. Adicione uma barra superior com um título

A barra deve possuir o ID "cabecalho" e deve ser fixa no topo da página com a propriedade top tendo **0**. O título deve estar dentro da barra e ser um elemento **h1** com ID "titulo".

**O que será verificado:**

- A barra possui o ID "cabecalho"
- A barra superior deve ser fixa no topo da página, com a propriedade top tendo o valor `0`
- O título deve estar dentro da barra e possuir o ID "titulo", além de ser uma tag "h1"

### 3. Adicione uma foto sua à página

A foto deve ser inserida utilizando uma tag **img** com o ID "minha_foto".

**O que será verificado:**

- A foto deve ser inserida utilizando uma tag img com o ID "minha_foto"

### 4. Adicione uma lista de lições aprendidas à página

A lista deve possuir **10** itens, ser numerada e possuir o ID "licoes_aprendidas".

**O que será verificado:**

- A lista deve ser numerada e possuir o ID "licoes_aprendidas"
- A lista deve possuir 10 itens

### 5. Crie uma lista de lições que ainda deseja aprender para a página

A lista deve possuir **10** itens, não ser numerada e possuir o ID "licoes_a_aprender".

**O que será verificado:**

- A lista não deve ser numerada e deve possuir o ID "licoes_a_aprender"
- A lista deve possuir 10 itens

### 6. Adicione um rodapé para a página

O rodapé deve utilizar a tag **footer** e possuir o ID "rodape".

**O que será verificado:**

- O rodapé deve possuir o ID "rodape"

### 7. Insira pelo menos um link externo na página

A configuração desse link deve ser feita para abrir em uma nova aba do navegador

**O que será verificado:**

- A configuração desse link deve ser feita para abrir em uma nova aba do navegador

### 8. Crie um artigo sobre seu aprendizado

O artigo deverá possuir mais de 300 **caracteres** e menos de 600, além disto deve possuir a tag **article**.

**O que será verificado:**

- A `tag` `article` devem ser utilizadas
- O artigo deve ter mais de 300 caracteres e menos de 600

### 9. Crie uma seção que conta uma passagem sobre seu aprendizado

A seção deverá possuir mais de 100 **caracteres** e menos de 300, além disto deve possuir a tag **aside**.

**O que será verificado:**

- A `tag` `aside` deve ser utilizada
- A seção deve ter mais que 100 caracteres e menos que 300

### 10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles

Para tornar o seu site mais acessível e melhorar seu ranqueamento em mecanismos de busca na Web, sua página deve conter os seguintes elementos: article, header, nav, section, aside e footer.

**O que será verificado:**

- Validar se a página possui um elemento "article"
- Validar se a página possui um elemento "header"
- Validar se a página possui um elemento "nav"
- Validar se a página possui um elemento "section"
- Validar se a página possui um elemento "aside"
- Validar se a página possui um elemento "footer"

### 11. Teste a semântica da sua página está aprovada pelo site CodeSniffer

Teste a semântica da sua página está aprovada pelo site CodeSniffer

**O que será verificado:**

- Seu site deve passar sem problemas na verificação de semântica do site CodeSniffer

### BÔNUS

### 12. Adicione uma tabela à página

**O que será verificado:**

- A página deve possuir uma tabela

### 13. Utilize o Box model

Altere **margin**, **padding** e **border** dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes.

**O que será verificado:**

- Altere `margin`, `padding` e `border` dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes

### 14. Altere atributos relacionados as fontes
Modifique o estilo da sua tipografia alterando o tamanho de letra, a cor, o espaçamento entre as linhas e a **font-family**.

**O que será verificado:**

- Altere o tamanho da letra
- Altere a cor da letra
- Altere o espaçamento entre as linhas
- Altere o `font-family`

### 15. Posicione o seu artigo e a seção sobre aprendizados um ao lado do outro

Adicione ao elemento posicionado no lado esquerdo a classe "lado-esquerdo" e ao elemento posicionado no lado direito a classe "lado-direito"

**O que será verificado:**

- Utilizar a classe "lado-esquerdo"
- Utilizar a classe "lado-direito"
- Verificar se os elementos com as classes lado-direito e lado-esquerdo estão posicionados corretamente

---