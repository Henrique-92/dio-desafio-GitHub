# Primeiro Projeto - DIO Git/GitHub



- #### Introdução 

  ######  Conhecendo um pouco do que será pedido 

- #### Git/GitHub: Relembrando algumas coisinhas 

   ###### Relembrando alguns comandos do Git, e revendo a como a criar um repositório no GitHub, e realizando a interligação dos dados da maquina local e no remoto entre o Git e GitHub.  

- #### Desafio 

   ###### Criar repertório com dicas e exercícios proposto pela equipe da Dio. 


## 		Introdução a HTML 5 :computer:

##### Links úteis:

- [Editor de texto VS Code ](https://code.visualstudio.com/)

- [Editor de texto Atom](https://atom.io/)

- [Editor de texto virtual Code Pen](https://codepen.io/)

- [Para tirar dúvidas em HTML 5](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web)



###### Passo a passo para inicializar nos editores de texto e começar a escrever seu código.

- Através do Editor VS Code e o Atom
  - Crie uma pasta para guardar o seu arquivo, em seguida crie um arquivo ex: "text.html".
  - Importante que ao criar o arquivo html se faz necessário acrescentar o nome do arquivo + .html e não começar com números, letras maiúsculas ou caracteres especiais. 
  - Ao criar o arquivo você irá digitar na primeira linha html, onde o próprio programa irá recomendar a estrutura básica. Ex: html:5

   Irá aparecer a estrutura básica. 

      <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>


###### - Através do Code Pen
   - É uma plataforma virtual que é possível escrever código sem precisar de um programa. Possibilitando começar a escrever através do celular móvel ou tablet. 
   - Para iniciar, basta utilizar os comandos do HTML5 
   - Click no link acima para aprender um pouco mais sobre HTML5 

  ###### - Comandos Importantes de HTML5 - Semânticas 

      <section></section> Representa uma seção generica de conteudo - lista de arquivos
      <footer></footer> Seria o rodapé para os contatos da página.   
      <article></article> Representa um conteudo relevante da página.
      <header></header> Cabeçalho de uma página.
      <aside></aside> Representa um conteudo relacional da página.
      <h1>-</h6> Do h1 e h2 é voltado para titulos, e os demais do h3 ao h6 podem ser subtitulos da página.

###### - Textos e Links

         <h1> Utilizado em sua mário como título da página.
         <h2> Utilizado como "subtítulo" da página.
         <h3> Utilizado como título de artigo.
         <p> Utilizado como texto comum dentro da página e cria espaço (parágrafos) entre os conteúdos da página.
         <a> É uma ancora que você pode utilizar para criar links ex: <a heref="link da página">Link</> ou <a target="_blank">Link</a> Irá abrir em uma nova aba. 

###### - Adicionando Imagens

         <img src="" alt=""> Através do comando é possível adicionar fotos. No " src="" " é o espaço para colocar o nome do arquivo junto com o tipo da foto (ex: png, jpg, jpeg e etc). O " alt="" " é possivel dar nome ao arquivo dentro da página para que aja facilidade em localizar caso apereça algum erro. 

###### - Listas

         <ul> Não segue uma ordem 
         <ol> Segue uma lista de itens ordenados
         <li> Representa um item que faz parte de uma lista <ol>


###### - Comandos Importantes de CSS com HTML5


      - Seletores de CSS

         São elementos HTML (a, p, h1, e etc) com obrigatoriedade de utilizar as chaves -> {} para mudar o estilo da página.
         
         Elemento de "Class" 
            Exemplo: HTML <img class="code">
                     CSS .code {}

         Elemento "ID"
            Exemplo: HTML <img id="code">
                     CSS #code {}

      Adicionando alguns elementos utilizando HTML e CSS

      <link rel="stylesheet" href="estilo.css">

      - Conceitos básicos de CSS

         Background: muda a cor de fundo de qualquer coisa

         Padding 15px (topo) 10px(direita) 5px(inferior) 0px(esquerda)

         Padding-top, padding-right, padding-bottom e padding-left

         Margin 15px (topo) 10px(direita) 5px(inferior) 0px(esquerda)
         Margin-top, Margin-right, Margin-bottom, Margim-left

      - Principais seletores do CSS

      Dimensão e alinhamento em CSS

      width
      height

      Max-width
      Max-height

      Margin - Alinha 

      Text align - Alinha o texto 


      CSS - FLEX BOX

       Flex Container  - itens filhos 

         display: flex
            div, span, h1, h2 e a 

       Propriedades 
         Display; inicializador do container
         flex-direction; faz direcionamento em linha ou coluna
         flex-wrap; quebra de linha
         flex-flow; é o direction e wrap juntos
         justify-content; alinha o container de acordo com a direação
         align-items; alinha de acordo com o eixo
         align-content; alinha as linhas do container
      
      Flex item 

      flex-grow
      flex-basis
      flex-shrink
      flex
      order
      align-self

      Display flex
       
      Flex Direction - Propriedade que direciona o eixo da coluna 

         Linha - Horizontal 
         Coluna - Vertival

         row; Direção do texo, esquerda para direita
         row-reverse; sentido oposto, da direita para esquerda. 
         column; ordenação de cima para baixo em coluna. 
         column-reverse; de baixo para cima. 

      Flex wrap - Quem define a quebra de linha ou não. 

         nowrap - é o pradrão, não permite quebra de linha.
         wrap - permite a quebra de linha assim que dos flex itens não puder mais ser compactado. 
         wrap-reverse - permite a quebra de linha porém na direção contrária. 

      Flex Flow - atalho para o flex-direction e flex wrap

         práticando

         flex-flow: row nowrap;
         flex-flow: row wrap;
         flex-flow: row wrap-reverse;
         flex-flow: row-reverse nowrap;
         flex-flow: row-reverse wrap;
         flex-flow: row-reverse wrap-reverse;
 
      Justify Content - Alinha os itens dentro do container de  acordo com a direção pretendida e trata da distribuição de espaçamento entre eles.

         Caso o container estiver ocupando 100% do espaço, o justify content não se aplica. 

         Variaçãos:

         flex-start: inicio do container
         flex-end: final do container
         center: centralização do container
         space-between: cria espaço igual entre os elementos
         space-around: os espaçamentos do meio são duas vezes maior que o inicio e o final. 
      
      Align-items - Trata o alimento de itens de acordo com o eixo do container. O alimento é diferente quando os itens estão em colunas ou linhas. Permite o alinhamento central no eixo vertical.

         Center - Alinhamento dos itens ao centro.
         stretch - padrão, e os flex itens cresçam igualmente.
         flex-star - alinhamento dos itens no inicio de acordo com o eixo.
         flex-end - alinhamento dos itens no final de acordo com o eixo. 
         baseline - alinhamento de acordo com a linha base da tipografia dos itens.
      
      Align-Content - Reponsável por tratar o alinhamento das linhas do conteiner no eixo vertical. 
         O container uttilize quebra de linhas
         A altura do container seja maior que a soma das linhas dos itens. 

         Tipos de alinhamento
            Center - alinhamento dos itens ao centro.
            Stretch - é o padrão e os flexs itens crescem igualmente.
            flex-start - alinhamento dos itens no inicio.
            flex-end - alinhamento dos itens no final.
            space-between - cria um espaçamento igual entre os elementos.
            space-around - os espaçamento do meio são duas vezes maiores que o inicial e o final.
      
      Flex Grow - Tem a função de se adaptar ao tamanho do container com a largura pré-estabelecida.

         Define a proporcionalidade de crescimento dos itens, respeitando o tamanho de seus conteudos internos.
         Não irá funcionar caso tenhamos adicionado justify-content ao nosso flex container. E só funciona com números.

      Flex Basis - Propriedade que estabelecee o tamanho inicial do item antes da distribuição de espaço restante dentro dele, usando como base o conteúdo interno disposto. 

         auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item. Se tiver flex-grow definido ele tentará ao tamanho definido. 
         px, %, em, ...: são valores exatoss previamente definidos. Se passar o valor do container, poderá vazar. 
         0 (zero): terá relação com a definição do flex-grow.

      Flex-shrink - É a propriedade que estabelece a capacidade de redução ou compreesão do tamanho de um item. É o funcionamento inverso do Flex Basis

      Flex - atalho ou abreviação de escrita para as propriedades: grow, shrink e basis.

      Order - Está relacionada a ordenação dos itens

      Align Self - Alinhamento individual sobre um determinado item

         Valores possíveis

            auto - valor padrão, que irá respeitar a definição de align-itens do container
            flex-start - ao inicio do container 
            flex-end - ao final do container
            center - centralizado ao container de acordo com o eixo (Column ou Row)
            stretch - ocupa todo o espaço relativo.
            baselina - utiliza a linha base da tipografia.
      



