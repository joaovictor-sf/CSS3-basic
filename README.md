# CSS3 Basic
CSS quer dizer folha de estilo em cascada, é feito para maior edição em uma página web.

O CSS3 pode ser feito de 3 formas: inline-style(dentro de uma tag), internal-style(dentro do head) ou em um arquivo externo.

Um seletor é utilizado para modificar uma tag de forma geral, sempre que ela aparecer ela terá essa característica a não ser que uma classe ou id diga o contrário.

    seletor {                           
            propriedade: valor;        
        }                               

    p {
        color: blue;
    }

No CSS existe classes e IDs, classes é uma caracteristica que se repete, como o sexo masculino e a id é uma caracteristica unica como o CPF.

Para criar uma classe:
    
    .nome {
    }

    Para criar um ID:
    #nome {
    }

No HTML5 existem duas tags muito utilizadas junto com o CSS, que são o &lt;div> e o &lt;span>, a diferença entre elas é que o div é do tipo block e o span é inline.

## Bordas
Podem ser configuradas de 10 maneiras: solid, dotted, dashed, double, groove, ridge, inset, outset, none, hidden e misturada.

## Cores

As cores podem ser escolhidas de 2 maneiras, com o nome(red) ou com um código (#6A1D1D, rgb(185, 23, 23)...).

Para achar a cor que deseje você pode ou utilizar o sistema de cores do VSCode ou procurar na web com: "Cores HTML5"

## Fontes

Para modificar a fonte do texto é utilizado font-family, é aconselhável por pelo menos uma fonte comum como serif para o caso de se o navegador do usuário não aceitar a fonte que escolheu ela irá mudar para a outra.

Ex:
    
    font-family: "Paladino Linotype", "Book Antigua", serif;

## Tamanho
Há 3 medidas de tamanho em HTML5/CSS3: px(pixel), em(relativa), %(relativa). 

As medidas em e % são relativas ao contêiner pai, no caso de não haver nenhum container os modificando o container pai é o body.

Em um site o default é: 16px, 1em e 100%(Isso para textos)

## Estilo de Texto
Assim como no HTML, o CSS também é possível modificar o estilo do texto(negrito, itálico...). Isso é recomendado somente quando é uma questão estética. Quando realmente tem um motivo para uma parte do texto estar em algum estilo é recomendável a utilização das tags HTML.

Deixar em <b>negrito</b>:
        
    font-weight: bold, normal, 100 ate 900
    
Deixar em <strong>itálico</strong>:
    
    font-style: italic;

Deixar com <strong>underline</strong>:
    
    text-decoration: underline;

Deixar com uma <strong>linha no meio do texto</strong>:
    
    text-decoration: line-through;

Deixar com uma <strong>linha acima do texto</strong>:
    
    text-decoration: overline;

## Background
Você pode colocar uma imagem como Background com:
    
    background-image: url("");

Com size você pode mudar o tamanho
    
    background-size: 10em;
    
Por default ela vai ser repetir, vc pode mudar isso ou modificar a repetição
    
    background-repeat: no-repeat/repeat-x/repeat-y/repeat(default);    
    
Com attachment vc pode decidir se a imagem muda de posição ou não quando o usuário sobe ou desce a página
    
    background-attachment: fixed;
    
Você pode deixar a imagem em uma posição específica da tela 
    
    background-position: center bottom;
    
Em vez de separado, você pode juntar tudo:
    
    background: url("https://www.pngmart.com/files/15/Falling-Money-PNG-Transparent-HD-Photo.png") no-repeat fixed green center bottom;

## Div/Span
Tag "div" serve para dividir as áreas do site, ela é um elemento do tipo block, quer dizer que ocupa todo o espaço da tela, como se tivesse uma largura de 100%.

    <div id="topo">
        <img src="https://logodownload.org/wp-content/uploads/2014/04/amazon-logo.png" alt="logo" width="200">
        <ul>
            <li> <a href="link.html">Home</a></li>
            <li>Contato</li>
            <li>Sobre</li>
        </ul>
    </div>

A tag "span" assim como o div serve para separar partes da página, mas diferente dele o span é do tipo inline.

Ele é mais utilizado para marcar uma parte de um texto ou de um documento

    Todos os direitos reservados a <span id="assinatura">João Victor</span>