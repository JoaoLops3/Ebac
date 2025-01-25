# CSS Parte 1

class no css usamos ponto final;

id no css usamos #;

# Parte 4 
## Configure a pagina com box sizing

box sizing : border-box;  -- serve para que o tamanho do elemento seja o tamanho da caixa, incluindo borda e padding;


*{
    box-sizing: border-box;
    margin : 0;
    padding : 0;
}

# Parte 5
## Defina o display

display inline; -- elementos são exibidos lado a lado;
display block; -- elementos são exibidos em uma linha, um em baixo do outro;
display none; -- elementos não são visíveis;
display flex; -- elementos tenta ocupar todo o espaço disponível;

.container{
    width: 1366px;
    margin: 0 auto;
}

.articles {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between; 
}

.articles articles img{
    height: 180px;
}

.articles article{
    width: 30%;
}