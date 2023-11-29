# DIO---Posicionando-elementos-com-flexbox-
Repositório para estudar alguns fundamentos inportantes de css

## usando o atribulo display: flex;

Quando estamos codando um código em html, normalmente para cada tag, o navegador gera uma coluna e desenha o componente um embaixo do outro, porem em muitos casos queremos deixar um texto ao lado do outro, como por exemplo, ao gerar um navbar com itens de menu, e para isso temos o nosso novo melhor amigo, sendo ele, o atributo css display:flex. Em resumo o que ele faz é concentrar todos os filhos em uma única linha, tentando respeitar ao máximo a distância entre os componentes, veja um exemplo:

```
    .flex{
        /* max-width: 500px; */ 
        padding: 20px;
        border: 2px solid green;
        display: flex;
    }
    .item{
        background-color: yellow;
        margin: 5px;****
    }

    <div class="flex">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
    </div>

```

 Como eu usei a classe flex no container pai, logo todos os filhos que estão dentro vão estar na horizontal. Em resumo: "display:flex" simplismente faz a troca de coluna para linha, é isso... depois disso podemos começar a brincar com outros conceitos, como exemplo, começar a renderização da direita pra esquerda:

 ```
    .flex{
        flew-direction: row-reverse; //add 
    }
 
 ```

