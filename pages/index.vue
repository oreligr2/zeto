<template>
  <div>
    <Header />
    <section class="section">
      <div class="container">
        <CategoryPreviews />
      </div>
      <div class="more">
        <a href="" class="btn btn_more">Больше категорий</a>
      </div>
    </section>

    <SearchComponents />

    <section class="section">
      <CatalogPreviews />
      <div class="more">
        <a href="" class="btn btn_more">Показать ещё</a>
      </div>
    </section>

    <section class="section">
      <h2 class="h2 text-center section_title">Новинки</h2>
      <CatalogPreviewsCarousel />
      <div class="more">
        <a href="" class="btn btn_more">Показать ещё</a>
      </div>
    </section>

    <section class="section">
      <h2 class="h2 text-center section_title">Вы просматривали</h2>
      <CatalogPreviewsCarousel />
    </section>

    <div class="block_dark block_dotes block_mb">
      <div class="container">
        <h2 class="h2 h2__light text-center">Комплектующие (запчасти) для Вашей техники</h2>
        <div class="block_text">
          <p>
            Интернет-магазин Zeto является крупнейшим каталогом комплектующих для ноутбуков в Украине и не имеет аналогов в мире, а также лидером на рынке оказания услуг ремонта ноутбуков, благодаря квалификации наших сервис-менеджеров и слаженной работе команды. О чем свидетельствуют многие положительные отзывы от наших клиентов.
          </p>
          <p>
            Наша компания предоставляет широкий спектр услуг по ремонту ноутбуков и их модернизации. У нас вы сможете купить и заменить отдельные комплектующие для ноутбуков, либо просто сделать заказ на запчасти для ноутбуков с доставкой на дом или в офис.
          </p>
          <p>
            У нас есть все для ноутбуков, такие комплектующие как матрицы, аккумуляторы, клавиатуры, зарядные устройства, жесткие диски, память и многое другое.
          </p>
          <a href="" class="arrow-more">
            <div class="arrow-more_text">
              Весь текст
            </div>
            <div class="arrow-more_img">
              <img src="../assets/icons/arrow-down.svg" alt="">
            </div>
          </a>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>
