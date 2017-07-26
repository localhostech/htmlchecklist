<h1>Чеклист верстки</h1>
<ol>
<li><b>Соответствие макету</b>
<p>Расположение блоков должно быть 1:1 по сравнению с макетом. Допускается расхождение до 5px для текста. Разрешены и даже приветствуются правки размеров и расположения криво нарисованных блоков (разница размерах в 1-2px на разных страницах).
</p>
</li>
<li><b>Кроссбраузерность, кодировка и DOCTYPE</b>
<p>Браузеры для проверки:<br>
Firefox (последний)<br>
Chrome (последний)<br>
iPhone+Android (стандартные браузеры)<br>
IE10<br>

В каждом из этих браузеров сайт должен отображаьться и работать одинаково, допускается downgrade стилей в Internet Explorer, но структура при этом не должна ломаться. 
</p>
<p><b>Кодировка: UTF-8</b></p><p>Первая строка любой страницы должна быть &lt;!DOCTYPE HTML&gt;</p></li>
<li><b>Проверить что все интерактивные элементы страницы что должны работать — работают.</b></li>
<li><b>Валидность css и js</b><p>Проверка осуществляется с помощью сервисов CSSLint и JSLint</p></li>
<li><b>Независимость блоков в CSS: использование техник БЭМ при именовании классов</b></li>
<li><b>Сайт должен нормально смотреться во всех стандартных разрешениях от 1024 и выше, не иметь горизонтального скролла и вписываться в экран мобильных устройств</b><br> Список классических разрешений: <br>
320x480<br>
1024x600<br>
1024x768<br>
1152x864<br>
1280x800<br>
1280x1024<br>
1440x900<br>
1680x1050<br>
1920x1080</li>
<li>В разметеке должны использоваться html5-тэги: header, footer, aside, nav, section, article и т.д. </li>
<li>Правильная структура заголовков (H1,H2,… и т.д. и TITLE) Заголовки не должны использоваться в header, footer, sidebar...</li>
<li>У картинок должны быть прописаны осмысленные alt.</li>
<li>Нельзя задавать визуальное отображение элементов через js: $('.element').css(color,"#f00"). Это должно делаться через установку/смену классов. Также запрещено использовать инлайновые стили в атрибуте style</li>
<li>Лого должно вести на главную страницу</li>
<li>Скорость сайта должана быть оптимизированна согласно советам <a href="https://developers.google.com/speed/pagespeed/insights/?hl=ru" target="_blank">Google PageSpeed Insights</a></li>
<li>Не должно быть js-ошибок! После выхода в продакшн удалить все console.log</li>
<li>Ссылки на чужие сайты должны быть с target="_blank" и rel="nofollow noopener"</li>
<li>Изображения должны масштабироваться в зависимости от размера окна (max-width:100%; height:auto;)</li>
<li>Картинки должны быть в отдельной папке, css — в отдельной и js — в отдельной. Графика, не являющаяся частью дизайна (всякие илююстрации, фото в новостях и т.д.) — нужно положить в отдельную папку, например uploads.</li>
<li>Ресайз textarea не должен ломать вёрстку. Когда не требуется запрещать ресайз через css свойство resize: none;</li>
<li>Все ссылки должны как-то реагировать на :hover, :active и :focus — показыванием/убиранием подчёркивания, сменой цвета, чем угодно. У всех ссылок, кроме пунктов меню, должна быть реакция на :visited</li>
<li>Уведомления должны выводиться текстом или с помощью различный модулей на сайте, ни в коем случае не использовать js alert()</li>
<li>Правильные input type=”email/url/tel”</li>
</ol>
