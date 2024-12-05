# Yandex Tracker {#yandex-tracker}

Моя основная редакция. К ней также относятся сервисы **Yandex Wiki** и **Yandex Forms**. У этих документаций есть версии для внешних пользователей и для сотрудников Яндекса.

Сейчас я в роли помощника лида:

- Отправляю документацию на перевод, проверяю и загружаю результат.

- Настраиваю конфиги для автоматических действий.

- Делаю другую организационную работу, если меня об этом попросят. Например, разбираю бэклог, пишу внутреннюю инструкцию или готовлю кое-какие документы))

### Что по текстам

* Как писатель я приложила руку почти к каждой странице. Дам ссылки на те, которые писала полностью сама:

  [Интерактивное руководство по Tracker](https://yandex.ru/support/tracker/ru/user/quick-guide)

  [Удалить задачу](https://yandex.ru/support/tracker/ru/user/ticket-cancel)

<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">Лондон</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Париж</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Токио</button>
</div>

<!-- Содержимое вкладки -->
<div id="London" class="tabcontent">
  <h3>Лондон</h3>
  <p>Лондон является столицей Англии.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Париж</h3>
  <p>Париж является столицей Франции.</p>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Токио</h3>
  <p>Токио является столицей Японии.</p>
</div>


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
