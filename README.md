Мои редакции:

- [Yandex Tracker](#yandex-tracker)
- [Алиса и умные устройства](#smart-home)
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

  ![](tracker.png) [~~Удалить задачу~~](#) <small>(еще не смержили)</small>

* Несколько раз редактировала интерфейсные тексты: например, всплывающие уведомления в Forms и онбординг в Tracker. К моему сожалению, эти блоки больше не отображаются в интерфейсе, а когда отображались — я их не заскринила. Нашла только скриншоты «до», а «после» нарисовала на коленке:

![](tracker.png) **Виджет «Время цикла»**
<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Стало</button>
</div>
<!-- Содержимое вкладки -->
<div id="London" class="tabcontent">
  <img src="3-3.jpg">
</div>
<div id="Paris" class="tabcontent">
  <img src="3.jpg">
</div>
<br>

![](tracker.png) **Копирование дашбордов и виджетов**
<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London1')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris1')">Стало</button>
</div>
<!-- Содержимое вкладки -->
<div id="London1" class="tabcontent">
  <img src="2-2.jpg">
</div>
<div id="Paris1" class="tabcontent">
  <img src="2.jpg">
</div>
<br>

![](tracker.png) **Диаграмма «Жизненный цикл задачи»**
<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London2')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris2')">Стало</button>
</div>
<!-- Содержимое вкладки -->
<div id="London2" class="tabcontent">
  <img src="1-1.jpg">
</div>
<div id="Paris2" class="tabcontent">
  <img src="1.jpg">
</div>
Не судите мои табы строго
<br>
<br>
* Еще я изменяла структуру разделов. Оценить изменения предлагаю в сравнении с [документацией на домене cloud](https://yandex.cloud/ru/docs/tracker/), которая нами больше не поддерживается:

![](tracker.png) **Раздел «Автоматизация и шаблоны»**
<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London4')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris4')">Стало</button>
</div>
<!-- Содержимое вкладки -->
<div id="London4" class="tabcontent">
  <p>Здесь ссылки расположены непоследовательно:</p>
  <p>1. из-под ката «Шаблоны» выпали еще две страницы с такой же тематикой;</p>
  <p>2. между страницами про шаблоны затесалась страница про переменные.</p>
  <p>Сходу непонятно, что здесь относится к автоматизациям, что к шаблонам и какая между ними связь.</p>
  <img src="templates-cloud.gif">
</div>
<div id="Paris4" class="tabcontent">
  <p>Теперь у каждой сущности есть свой понятный раздел.</p>
  <p>Страница <a href="https://yandex.ru/support/tracker/ru/manager/work-process">Шаблоны рабочих процессов</a> переехала в другой раздел: все-таки эти шаблоны относятся к базовым настройкам Tracker, и информацию про них ряд-ли станут искать в разделе про шаблоны для типовых комментариев.</p>
  <img src="templates-docs.gif">
</div>
<br>

![](tracker.png) **Раздел «Статистика и дашборды»**
<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London3')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris3')">Стало</button>
</div>
<!-- Содержимое вкладки -->
<div id="London3" class="tabcontent">
  <p>Что здесь не так?</p>
  <p>1. В разделе «Дашборды» прячется еще одна сущность  — «Виджеты». Она нигде не заявлена, а пользователь может не знать, что между дашбордами и виджетами есть связь и информацию про них нужно искать именно под этим катом.<br>Пояснение: виджет — это дополнительный блок для дашборда.</p>
  <p>2. А вот зачем в заголовке заявлена статистика — непонятно, раздел не о ней. Про статистику всего две страницы: «Статистика по задачам», которая является виджетом, и «Статистика очереди», которая отображается в другом месте и никакого отношения к дашбордам и виджетам не имеет.</p>
  <img src="dashboard-cloud.gif">
</div>
<div id="Paris3" class="tabcontent">
  <p>Теперь раздел посвящен двум связанным сущностям: дашбордам и виджетам.</p>
  <p>Страница <a href="https://yandex.ru/support/tracker/ru/manager/statistics">Статистика очереди</a> не относится к теме и отправилась в другой раздел.</p>
  <img src="dashboard-docs.gif">
</div>
---

## Алиса и умные устройства {#smart-home}

Это объемная документация со сложной структурой. С ней я работаю как дополнительный писатель. Здесь мне приходится кропотливо чинить сломанные YFM-разметку и CSS-стили для разводящих страниц (например, <img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Умная розетка](https://alice.yandex.ru/support/ru/socket/) и <img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Решение проблем](https://alice.yandex.ru/support/ru/station/troubleshooting/)), работать с инклюдами и переменными.  Здесь же застала технологию DITA на языке XML.

<u>Еще была интересная задача:</u> с помощью ИИ я сгенерировала около сотни ссылок на адреса сервисных центров в Яндекс Картах и добавила их в таблицы в виде кнопки «Посмотреть на карте». Вот одна из страниц с такими таблицами: 

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Замена и ремонт](https://alice.yandex.ru/support/ru/services)

### Что по текстам 

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Алиса сообщает о проблеме со Станцией или молчит](https://alice.yandex.ru/support/ru/station/troubleshooting/assistant-reports#tape)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Сценарии с группами устройств](https://alice.yandex.ru/support/ru/smart-home/scenarios/device-group)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Проблемы с устройствами Matter™](https://alice.yandex.ru/support/ru/smart-home/third-party/troubleshooting/matter)

<img src="https://yastatic.net/s3/doc-binary/docs/support/selfhost/alice/station/smart-home-app.svg" alt="" yfm_patched="1" height="20px"> [Почему на Станции горит зеленая подсветка](https://alice.yandex.ru/support/ru/station/troubleshooting/green-light)

---

## Яндекс Фабрика {#yandex-factory}

Придумыванием и согласованием структуры этого кластера занимаются продюсеры и штатный менеджер, но как исполнитель я работаю над ним полностью сама. Работа с текстом здесь минимальная, скорее техническая часть:

1. Создала документацию на Diplodoc с нуля, в том числе настроила конфиги.

2. Создавала кнопки и карточки в Figma, делала CSS-оформление таблиц.

3. Предлагала структуру и защищала свои идеи.

<u>Как только ссылка появится в продакшене, я обязательно ее добавлю)</u>


<style>
/* Стиль вкладки */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Стиль кнопок, которые используются для открытия содержимого вкладки */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}

/* Изменение цвета фона кнопок при наведении курсора */
.tab button:hover {
  background-color: #ddd;
}

/* Создание активного/текущего класса связи вкладки */
.tab button.active {
  background-color: #ccc;
}

/* Стиль содержимого вкладки */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>

<script>
function openCity(evt, cityName) {
  // Объявить все переменные
  var i, tabcontent, tablinks;

  // Получить все элементы с помощью class="tabcontent" и спрятать их
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Получить все элементы с помощью class="tablinks" и удалить class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Показать текущую вкладку и добавить "active" класс для кнопки, которая открыла вкладку
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
