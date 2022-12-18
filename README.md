# week8
1. Основное преимущество в том, что он он облегчает верстку и позволяет работать намного быстрее. Не нужно прописывать руками каждый элемент, можно взять готовый шаблон в бутстрапе

2. <button type="button" class="btn btn-warning">

3. Я честно пыталась сделать с помощью сетки бутстрап, но у меня сломался мозг, и я сделала на гридах за 3 минуты))) подумала, это будет лучше, чем ничего)

<style>
      .container {
        color: white;
        display: grid;
        grid-gap: 5px;
        height: 70vh;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 10% 50% 20% 20%;
        grid-template-areas:
          "gallery title"
          "gallery buybox"
          "description description"
          "related related";
      }
      .gallery {
        display: grid;
        grid-area: gallery;
        background-color: rgb(73, 118, 191);
        text-align: center;
        align-items: center;
      }
      .title {
        display: grid;
        text-align: center;
        align-items: center;
        grid-area: title;
        background-color: rgb(73, 118, 191);
      }
      .buybox {
        display: grid;
        text-align: center;
        align-items: center;
        grid-area: buybox;
        background-color: rgb(73, 118, 191);
      }
      .description {
        display: grid;
        text-align: center;
        align-items: center;
        grid-area: description;
        background-color: rgb(73, 118, 191);
      }
      .related {
        display: grid;
        text-align: center;
        align-items: center;
        grid-area: related;
        background-color: rgb(73, 118, 191);
      }
    </style>
  </head>

  <body>
    <div class="container">
      <div class="gallery">Gallery</div>
      <div class="title">Title</div>
      <div class="buybox">Buy box</div>
      <div class="description">Description</div>
      <div class="related">Related</div>
    </div>
  </body>

  4. С помощью прогрессбар

  5. У row нужно задать дополнительный класс .no-gutters

  6. С помощью компонентов navbar

  7. Auto-layout колонки позволяют использовать больше 12 колонок в строке. 12 колонок располагаются как обычно горизонтально по строке, а все "лишние" встают вертикально вниз. Это называется враппингом колонок.

  8. Нужно задать <div class="row justify-content-center"> или <div class="row align-items-center">

  9. <div class="col-12 col-md-6">

  10. Они начнут вставать вертикально вниз на следующей строке, произойдет враппинг колонок

  11. Сначала подключаем Font Awesome к проекту, затем вставляем иконку через <i class="fa fa-instagram"></i>

  12. сontainer создает блок по центру экрана, а container-fluid растягивает блок по всей ширине