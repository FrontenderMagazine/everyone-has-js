<style>
dl.graph dt{
  background-color: #E05A2B;
  border-radius: 10px;
  padding: 10px;
  color: #fff;
  box-shadow: 0 10px 0 0 #DD4814;
  font-size: 14px;
  line-height: 16px;
  text-transform: uppercase;
  }
dl.graph dd{
  margin: 0 0 0 100px;
  padding: 20px 0 80px 20px;
  border-left: 1px dotted #77216F;
  position: relative;
  }
  dl.graph dd:after{
    content: "";
    display: block;
    position: absolute;
    height: 0;
    width: 0;
    overflow: hidden;
    font-size: 0;
    line-height: 0;
    border-width: 5px 5px 0;
    border-color: #77216F transparent transparent;
    border-style: solid;
    bottom: 0;
    left: -5px;
    }
  dl.graph dd div{
    background-color: #843E64;
    border-radius: 10px;
    padding: 10px;
    color: #fff;
    box-shadow: 0 10px 0 0 #772953;
    font-size: 14px;
    line-height: 16px;
    }
</style>

<h1>У всех есть JavaScript, да?</h1>

<dl class="graph">
  <dt>Пользователь набрал в браузере url веб-приложения.</dt>

  <dt>Страничка загрузилась?</dt>
  <dd><div>«Ни у одного пользователя нет JS, пока не скачались скрипты» — <a href="https://t.co/uTM3255RuW">Джейк Арчибальд</a></div></dd>

  <dt>HTTP запросы скриптов выполнены успешно?</dt>
  <dd><div>Если пользователь едет в поезде и соединение пропадает до того, как загрузились скрипты, то считайте, что JavaScript у него нет.</div></dd>

  <dt>HTTP запросы скриптов завершились?</dt>
  <dd><div>Сколько раз вы сталкивались с тем, что мобильный браузер вечно грузил страничку и загружал её мгновенно после обновления?</div></dd>

  <dt>Корпоративный фаервол не блокирует JavaScript?</dt>
  <dd><div>Я спрашиваю об этом потому, что многие из них именно так и делают. До сих пор.</div></dd>

  <dt>Интернет провайдер или мобильный оператор не изменяет скачиваемый JavaScript?</dt>
  <dd><div><a href="http://www.theguardian.com/technology/2014/jan/28/sky-broadband-blocks-jquery-web-critical-plugin">Sky случайно блокировал jQuery</a>, <a href="http://aaron-gustafson.com/notebook/2014/the-network-effect/">Comcast добавляет рекламу в скрипты</a>, и если вы с этим не сталкивались, то поезжайте в аэропорт и попробуйте использовать там wifi.</div></dd>

  <dt>Они не взяли и не отрубили JavaScript?</dt>
  <dd><div>Люди <a href="https://gds.blog.gov.uk/2013/10/21/how-many-people-are-missing-out-on-javascript-enhancement/">всё ещё так делают</a>.</div></dd>

  <dt>У пользователя нет плагинов или расширений, которые вставляют скрипты или меняют DOM там, где вы этого точно не ожидаете?</dt>
  <dd><div>Есть тысячи браузерных расширений. Вы уверены, что они ничего не делают с вашим JS?</div></dd>

  <dt>CDN работает?</dt>
  <dd><div>Суть CDN именно в том, что бы быть <em>надежным</em> но <a href="http://www.cdnperf.com/">минута в месяц, когда он не работает</a> всё же оставит без скриптов тех пользоваталей, кто в эту минуту загружает вашу страничку.</div></dd>

  <dt>Браузер поддерживает JavaScript который вы написали?</dt>
  <dd><div>Воспользуйтесь <a href="http://caniuse.com/">Can I Use</a>, что бы проверить.</div></dd>

  <dt>
    <p>Вы на все вопросы выше ответили «да»?</p>
    <p>Тогда, да, JavaScript работает. <strong>Возможно.</strong></p>
  </dt>
  <dd><div>
    <p><a href="http://jakearchibald.com/2013/progressive-enhancement-still-important/">Прогрессивное улучшение</a>. Потому что иногда JavaScript просто не работает.</p>
    <p>Стоит быть к этому готовым.</p></div>
  </dd>

</dl>
