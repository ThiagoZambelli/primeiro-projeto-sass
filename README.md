![Alt text](img/readme-imgs/SASS%20projeto.png)
<h1 align="center">Primeiro projeto de SASS<h1>

<hr />

## Assuntos tratados no curso ->

### Aula 1:
> Aula introdutoria sobre o SASS, explicando como ele funciona e como pode ser utilizado. Utilizamos `@mixin` e `@include` para otimizar codigos repetidos e $'variavel':'valor'; para criação de variaveis dinamicas;

- Entendemos o que é Sass e como podemos manter nossas folhas de estilos criando variáveis e funções;
- Instalamos o compilador do Sass através de uma extensão do VSCode;
- Vimos que podemos aninhar as classes de estilos com Sass, semelhante ao código HTML.

### Aula 2:
> Aula onde iniciamos o projeto de fato, onde trabalharesmo as propriedades do SASS a fundo, como a fragmentação de folhas SCSS em pequenos fragmentos `_[nome do fragmento sem conchetes]` que sao traduzidos pelo copilador SASS para uma folha de css unica aumentando o desempenho da aplicação.

- Carregamos o projeto base que vamos estilizar neste treinamento com Sass;
- Organizamos os arquivos de estilos criando partials, que contêm pequenos trechos de CSS que podem ser incluídos em outros arquivos Sass;
- Modularizamos o CSS tornando as folhas de estilos mais fáceis de manter;
- Estilizamos o navbar e incluímos o efeito hover através do operador &.

## Aula 3:
> Aula onde tratamos de escopo de varivais e a utilização das mesmas com formulas matematicas, como usar a divisao para garantir simetria no tamanho de fontes.

- Criamos a partial para manter os estilos do banner e posicionamos a imagem e os textos;
- Realizamos operações matemáticas para ajustar os tamanho dos textos das tags h1 e do h2;
- Vimos de forma prática que as variáveis declaradas no nível superior de uma folha de estilo são globais, porém aqueles declarados em blocos geralmente são locais e só podem ser acessados dentro do bloco em que foram declarados.

## Aula 4:
> Criação do campo de cupom e alinhamento dos cards (`Infinitamente mais simples de estilizar`).

- Modularizamos os códigos de estilo criando a partial de serviço e cupom;
- Aplicamos os estilos nas imagens e nos textos melhorando a visibilidade do SPA.

<hr />

#### Palavras reservdas :
- ``@use`` ->	carrega mixins, functions e variáveis de outras folhas de estilos Sass e combina o CSS de diversas folhas de estilo juntos.
- ``@forward`` ->	carrega uma folha de estilo Sass e torna os mixins, functions e variáveis disponíveis quando a folha de estilo é carregada pela regra do @use.
- ``@import`` ->	estende as regras de CSS para carregar styles, mixins, functions e variáveis de outras folhas de estilo.
- ``@mixins`` -> e @include	facilitam a reutilização de trechos de código.
- ``@function`` ->	define funções customizadas que podem ser utilizadas em expressões.
- ``@extend`` ->	permite que os seletores herdem estilos uns dos outros.
- ``@at-root`` ->	coloca estilos dentro dele na raiz do documento CSS.
- ``@error`` ->	faz com que a compilação falhe com uma mensagem de erro.
- ``@warn`` ->	imprime um aviso sem parar totalmente a compilação.
- ``@debug`` ->	imprime uma mensagem para fins de debugging.