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


<div onclick="look('div1')" class="box">
    <!-- название ката -->
    <h2>Кат: что делает фронтенд</h2>
    <!-- скрытый блок, который появится при нажатии -->
    <div id = "div1" style="display: none">
      <!-- сюда можно вставлять любое содержимое с любой сложностью вёрстки -->
      <ul>
        <li>собирает сайт по макету дизайнера;</li>
        <li>использует для этого HTML, CSS, JavaScript и несколько других языков;</li>
        <li>понимает процессы, которые происходят во время создания сайта;</li>
        <li>знает, как опубликовать сайт в Сети так, чтобы он выглядел одинаково на всех устройствах;</li>
        <li>умеет работать с Git или другим инструментом контроля версий;</li>
        <li>использует Webpack для сборки проекта и вообще оперирует препроцессорами.</li>
      </ul>
      <p> Звучит сложно, но вот основное: фронтенд берёт макет будущего сайта (картинку) и превращает его в код, который можно отправить клиенту. При необходимости он программирует интерактивные элементы и анимацию, которые будут обрабатываться на клиенте. </p>
      <p>Часто фронтендов путают с верстальщиками, но на самом деле верстальщик — это специалист узкого профиля (вёрстка по макету). А фронт кроме этого может и слайдер прикрутить, и шаблон в CMS поправить, и закодить нестандартное поведение картинки при нажатии, и написать скрипт для проверки правильности заполнения данных на сайте.</p>

    </div>
  </div>

<!-- Ссылки вкладки -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">Было</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Стало</button>
</div>

<!-- Содержимое вкладки -->
<div id="London" class="tabcontent">
  <h3>Было</h3>
  <p>Лондон является столицей Англии.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Стало</h3>
  <p>Париж является столицей Франции.</p>
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

<style type="text/css">
  /*  общие стили для страницы  */
	body {
    text-align: left;
    margin: 10;
    background: #e0e0e0;
  }
  h2{
    font-weight: 100;
    font-size: 30px;
    margin-bottom: 30px;
  }
  /*  настройки внешнего вида блока с катом  */
  .box{
    font-family: Verdana, Arial, sans-serif;
    line-height: 24px;
    font-size: 16px;
    font-weight: 200;
    border-radius: 24px;
    padding: 24px;
    margin: 20px;
    cursor: pointer;
    background: white;
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

<!-- скрипт, который раскрывает и закрывает кат -->
  <script type= "text/javascript">

    function look(type){
    // получаем доступ к блоку, который нужно показать при нажатии
    param=document.getElementById(type);
    // если его нет на экране — показываем
    if(param.style.display == "none") param.style.display = "block";
    // иначе — скрываем
    else param.style.display = "none"
    }
  </script>
