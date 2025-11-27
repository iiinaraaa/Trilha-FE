# setup
- importar o reset ✅
- criar as cores ✅
- importar as google fonts ✅
- criar var sass p breakpoints, tem que ter um arquivo p isso ✅
- criar as tipografias de h1 ate h6 e body, pra isso funcionar tem que ter os breakpoints ✅
- criar um html com os h1s h6s e body provando que eles sao responsivos ✅
- criar componente de button, e ele tem uma variante dark ✅
- fazer um componente de imagem responsiva (ex do guanabara) ✅
- criar um html com uma imagem e provar que ela eh responsiva (ex do guana) ✅
- criar um html com grid provando que ela funciona ✅


# atomos

- icon (rede social dos cabecas) variante redonda pqna, variante tamanho de icone medio (our feature) e os grandes (features) (fazer a caixinha com border radious e a imagem), tem que ter variantes de tamanho e cor ✅


# moleculas


# componentes

- Meet our team ✅ 
- variantes do meet out team ✅

- our features / features ✅ 
- features small ✅
- features variable ✅

- list logos / variante ✅

- our metrics ✅
- variante our metrics ✅

- real stories cards 
- variantes real cards (nao precisa por o background ainda, so quando costurar)

- card plans

- get landing page botar so o telefone ali

- more than 50 integration (logos)

- forms

- footer

# anotacao:

- por padding-bottom nas coisas, top nao eh necessario

- parar de usar -- p tablet e desktop e usar breakpoint agora.. nos proximos 

- lembrar que as imagens tbm tem que ter tamanho e altura, e tambem ter border radious caso ela seja redonda

- lembrar de por padding bottom nas coisas

- lembrar de commitar todos os dias

- vou adotar o camelcase nesse projeto

- na questao de img e medias eh bom usar aspect-ratio por conta de responsividade

- e se usa aspect-ratio em divs, com imagem dentro:

&-contentImage {
    aspect-ratio: 315/278;
    overflow: hidden;
    border-radius: 20px 20px 0 0;

    @media (min-width: bp.$tablet) {
        aspect-ratio: 213 / 173;
    }

    &-img {
        width: 100%;
        height: auto;
    }
}

- nem sempre precisamos definir height pras coisas pq isso quebra tudo as vezes

- MARGIN: 0 AUTO: isso aqui alinha no meio sem precisar usar flex ou grid, mas precisa acompanhar um max-width ou display: block;




# to do :

- arrumar os outros projetos, fazer ele ser responsivo, e nao fazer eles separadinhos ✅

- arrumar o padrao no nome das pastas que eu to fznd no storypobre ✅

TODO Por o projeto no vercel pra facilitar acesso dos mentores

TODO arrumar o bem nos icons
















