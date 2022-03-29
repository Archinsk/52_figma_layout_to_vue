<template>
  <div class="measures">
    <div class="measures-header">
      <nav class="header-nav">
        <ul class="header-nav-list">
          <li class="header-nav-list__item">
            <a href="#" class="header-nav-list__link">Сервис</a>
          </li>
          <li class="header-nav-list__item">
            <a href="#" class="header-nav-list__link">Программы развития</a>
          </li>
          <li class="header-nav-list__item">
            <a href="#" class="header-nav-list__link">Меры поддержки</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="measures-main">
      <nav class="measures-nav">
        <ul class="measure-nav-list">
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Поиск парнеров</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Межотраслевые кластеры</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link"
              >Биржа контрактного пр-ва</a
            >
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Биржа патентов</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Помещения в аренду</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Факторинг</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Маркетплейс продукции и услуг</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Получение статуса технопарка</a>
          </li>
          <li class="measure-nav-list__item">
            <a class="measure-nav-list__link">Технологический брокеридж</a>
          </li>
        </ul>
      </nav>
      <div class="measures-content">
        <div class="measures-content-info">
          <h4 class="measures-content-title">
            Подбор потенциальных партнеров c помощью искусственного интеллекта
          </h4>
          <p class="measures-content-text">
            Введите ключевой запрос, и система подберет вам релевантных
            партнеров на основе данных из личных кабинетов компаний.
          </p>
          <button class="btn btn-black measures-content-button">
            Узнать больше
          </button>
        </div>
        <svg width="500" height="463" viewBox="0 0 500 463" fill="none" class="measure-content-image">
          <path
            d="M0 427.136V262.593C68.625 262.506 134.41 234.802 182.905 185.565C231.4 136.329 258.639 69.5872 258.639 0L421.092 0C421.006 113.232 376.618 221.804 297.671 301.885C218.723 381.966 111.667 427.012 0 427.136Z"
            fill="url(#pattern0)"
          />
          <pattern id="pattern0" patternUnits="userSpaceOnUse" width="100%" height="428">
            <image class="svg-image" xlink:href="../assets/sotr.jpg" height="100%"></image>
          </pattern>
        </svg>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
