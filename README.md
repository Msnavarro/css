principal {
    exibição : flexível;
    flex-direction : coluna;
    largura :  100 % ;
    imagem de fundo :  url ( '../src/bg.jpg' );
    tamanho do fundo : capa;
    min-altura :  100 vh ;
    align-items : centro;
    justificar-conteúdo : centro;
    preenchimento :  20px 20px 50px ; _  _  _
}

cabeçalho {
 exibição : flexível;
 align-items : centro;
 justificar-conteúdo : espaço entre;
 cor de fundo :  rgba ( 255 ,  255 ,  255 ,  0,8 );
 tamanho da fonte :  1,2 em ;
 largura :  100 % ;
 largura máxima :  800 px ;
 preenchimento :  30px ; _
 margem :  0  0  15 px ;
 raio da borda :  5 px ;
}

. grade {
    exibição : grade;
    largura :  100 % ;
    largura máxima :  800 px ;
    grid-template-columns :  repeat ( 5 ,  1 fr );
    intervalo :  15 px ;
    margem :  0 automático;
}

. cartão {
    largura :  100 % ;
    relação de aspecto :  3/4 ;
    raio da borda :  5 px ;
    posição : relativa;
    transição : todos os 400 ms de facilidade;
    transform-style : preserve-3d;
}

. rosto {
    largura :  100 % ;
    altura :  100 % ;
    posição : absoluta;
    tamanho do fundo : capa;
    posição de fundo : centro;
    borda :  verde sólido de 2 px ;
    raio da borda :  5 px ;
    transição : todos os 400 ms de facilidade;
}

. frente {
    transform :  girarY ( 180 graus );
}

. voltar {
    imagem de fundo :  url ( '../src/back.png' );
    backface-visibility : oculto;
}

. carta-revelar {
    transform :  girarY ( 180 graus );
}

. cartão desativado {
    filtro : saturar ( 0 );
    opacidade :  0,5 ;
}
