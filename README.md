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