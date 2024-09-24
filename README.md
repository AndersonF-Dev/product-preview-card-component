# Frontend Mentor - Product preview card component solution

Esta é uma solução para o [Resumo dos resultados do desafio do componente no Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Os desafios do Frontend Mentor me ajuda a melhorar as habilidades de codificação construindo projetos realistas.



### Screenshot
Desktop-preview
[<img src="Desktop-preview.gif" alt="gif da tela inicial do projeto Product preview card component">]

Mobile-preview
[<img src="Mobile-preview.gif" alt="gif da tela inicial do projeto Product preview card component">]


### Link


- URL do site ativo: [link aqui](https://andersonf-dev.github.io/product-preview-card-component/)



### Criado com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Grid



### O que aprendi

Aprendi a criar uma card com grid responsivo, posicionar elementos na tela centralizar e carregar uma imagem direto no CSS.




```css
body {
    display: grid;
    grid-template-areas: "card-content card-content";
    grid-template-columns: repeat(1, 1fr);
    background-color: hsl(30, 38%, 92%);
    
}
.card-content {
    grid-area: card-content;
    display: grid;
    grid-template-columns: 1fr 1fr;
    max-width: 600px;
    margin: auto auto;
}

.img-product{
    background: url('../images/image-product-desktop.jpg') center center no-repeat;
    background-size: cover;
    width: 300px;
}

@media (max-width: 620px){
    .card-content{
        grid-template-columns: 1fr;
        grid-template-rows: repeat(1, 1fr);
    }
    .card-content .img-product {
        background: url('../images/image-product-mobile.jpg') center center no-repeat;
        background-size: cover;
        width: 345px;
        height: 241px;
        border-bottom-left-radius: 0px;
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
    }
```

### Desenvolvimento contínuo

Este é apenas o quarto de muitos dos projetos de front end que fiz. Continuarei fazendo e me desenvolvendo ainda mais. Estou aprendendo cada dia mais, fazendo esses desafios, estou fazendo sempre só.

Este sem duvidas foi o meu maior desefio ate agora porcom ta do (grid-template-areas) tive que fazer vaias consutas na internet. 
Os desafios fazem as pessoas crescerem na vida e profissionalmente. Que venha o próximo desafio.
