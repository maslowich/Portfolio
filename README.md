Мои редакции:

- [Yandex Tracker](#yandex-tracker)
- [Умный дом Яндекса](#smart-home)
- [Yandex Factory](#yandex-factory)

---

## Yandex Tracker {#yandex-tracker}

Моя основная редакция. К ней также относятся сервисы **Yandex Wiki** и **Yandex Forms**. У этих документаций есть версии для внешних пользователей и для сотрудников Яндекса.

Сейчас я в роли помощника лида:

- Отправляю документацию на перевод, проверяю и загружаю результат.

- Настраиваю конфиги для автоматических действий.

- Делаю другую организационную работу, если меня об этом попросят. Например, разбираю бэклог, пишу внутреннюю инструкцию или готовлю кое-какие документы))

### Что по текстам

* Как писатель я приложила руку почти к каждой странице. Дам ссылки на те, которые писала полностью сама:

  ![](tracker.png) [Интерактивное руководство по Tracker](https://yandex.ru/support/tracker/ru/user/quick-guide)

  ![](tracker.png) [~~Удалить задачу~~](#) (еще не смержили)

* Несколько раз редактировала интерфейсные тексты: например, всплывающие уведомления в Forms и онбординг в Tracker. К моему сожалению, эти блоки больше не отображаются в интерфейсе, а когда отображались — я их не заскринила. Нашла только скриншоты «до», а «после» нарисовала на коленке:

<div class="tabs-container">
  <ul class="tabs">
    <li class="active">
      <a href="">Part 1</a>
    </li>
    <li>
      <a href="">Part 2</a>
    </li>
  </ul>
  <div class="tabs-content">
    <div class="tabs-panel active" data-index="0">
      <img src="3-3.jpg">
    </div>
    <div class="tabs-panel" data-index="1">
      <img src="3.jpg">
    </div>
  </div>
</div>

<div class="tabs-container">
  <ul class="tabs">
    <li class="active">
      <a href="">Part 1</a>
    </li>
    <li>
      <a href="">Part 2</a>
    </li>
  </ul>
  <div class="tabs-content">
    <div class="tabs-panel active" data-index="2">
      <img src="2-2.jpg">
    </div>
    <div class="tabs-panel" data-index="3">
      <img src="2.jpg">
    </div>
  </div>
</div>

<div class="tabs-container">
  <ul class="tabs">
    <li class="active">
      <a href="">Part 1</a>
    </li>
    <li>
      <a href="">Part 2</a>
    </li>
  </ul>
  <div class="tabs-content">
    <div class="tabs-panel active" data-index="4">
      <img src="1-1.jpg">
    </div>
    <div class="tabs-panel" data-index="5">
      <img src="1.jpg">
    </div>
  </div>
</div>
---

## Умный дом Яндекса {#smart-home}

Это объемная документация со сложной структурой, с которой я работаю как дополнительный писатель. Здесь мне приходится кропотливо чинить сломанные YFM-разметку и CSS-стили для разводящих страниц (например, <img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Умная розетка](https://alice.yandex.ru/support/ru/socket/) и <img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Решение проблем](https://alice.yandex.ru/support/ru/station/troubleshooting/)), работать с инклюдами и переменными.  Здесь же застала технологию DITA на языке XML.

<u>Еще была интересная задача:</u> с помощью ИИ я сгенерировала около сотни ссылок на адреса сервисных центров в Яндекс Картах и добавила их в таблицы как кнопку «Посмотреть на карте». Вот одна из страниц с такими таблицами: 

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Замена и ремонт](https://alice.yandex.ru/support/ru/services)

### Что по текстам 

[Алиса сообщает о проблеме со Станцией или молчит](https://alice.yandex.ru/support/ru/station/troubleshooting/assistant-reports#tape)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Сценарии с группами устройств](https://alice.yandex.ru/support/ru/smart-home/scenarios/device-group)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Проблемы с устройствами Matter™](https://alice.yandex.ru/support/ru/smart-home/third-party/troubleshooting/matter)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Почему на Станции горит зеленая подсветка](https://alice.yandex.ru/support/ru/station/troubleshooting/green-light)

---

## Yandex Factory {#yandex-factory}

Придумыванием и согласованием структуры этого кластера занимаются продюсеры, но как исполнитель я работаю над ним полностью сама. Работа с текстом здесь минимальная, скорее техническая часть:

1. Создала документацию на Diplodoc с нуля, в том числе настроила конфиги.

2. Создавала кнопки и карточки в Figma, делала CSS-оформление таблиц.

3. Предлагала структуру и защищала свои идеи.

<u>Как только ссылка появится в продакшене, я обязательно ее добавлю)</u>


<style>
@media screen and (max-width: 600px) {
  .tabs {
    flex-direction: column;
  }
    
  .tabs li {
    width: 100%;
  }
    
  .tabs li:not(:last-child) {
    margin-right: 0;
  }
    
  .tabs li a {
    border-radius: 0;
    opacity: 1;
    top: 0;
  }
    
  .tabs li.active a::before {
    content: '•';
    padding-right: 5px;
  }
    
  .tabs-content {
    border-radius: 0;
  }
}
</style>

<script>
const tabLinks = document.querySelectorAll(".tabs a");
const tabPanels = document.querySelectorAll(".tabs-panel");
for(let el of tabLinks) {
  el.addEventListener("click", e => {
    e.preventDefault();
    
    document.querySelector('.tabs li.active').classList.remove("active");
    document.querySelector('.tabs-panel.active').classList.remove("active");
    const parentListItem = el.parentElement;
    parentList.classList.add("active");
    const index = [...parentListItem.parentElement.children].indexOf(parentListItem);
    
    const panel = [...tabPanels].filter(el => el.getAttribute("data-index") == index);
    panel[0].classList.add("active");
  });
}
</script>
