# 32-33
Анна

1-Пользователей не устраивает «чистый» HTML, так как он статичен, не предоставляет интерактивности и гибкости при взаимодействии с содержимым, а также не может адаптироваться под разные условия (например, пользовательский ввод)

2-Динамический HTML (DHTML) - это набор технологий, позволяющий создавать интерактивные и изменяемые интерфейсы. Он включает HTML, CSS и JavaScript. DHTML позволяет изменять содержимое и стиль страницы без перезагрузки

3-DHTML отличается от HTML тем, что DHTML позволяет динамически изменять содержимое и структуру веб-страницы, используя JavaScript и другие технологии, в то время как HTML представляет собой статическую разметку

4-JavaScript-код — это набор инструкций и команд, написанных на языке JavaScript, которые выполняются браузером для создания динамических и интерактивных веб-страниц

5-DOM (Document Object Model) — это структура данных, представляющая HTML-документ в виде дерева объектов. Она позволяет программно взаимодействовать с элементами страницы, изменять их содержимое, стили и структуру

6-Для поиска нужного элемента на веб-странице с помощью JavaScript можно использовать методы, такие как `document.getElementById()`, `document.querySelector()`, или `document.getElementsByClassName()`

7-Ролл-овер — это эффект изменения состояния элемента при наведении мыши. Примеры, когда этот эффект полезен: выделение ссылок для лучшего восприятия или смена изображения при наведении курсора на миниатюру

8-Событие — это действие или изменение состояния, происходящее на веб-странице, например, клик мыши, наведение курсора, изменение текста в поле ввода. В приведённых примерах мы работали с событиями клика и наведения

9-Обработчик события — это функция, которая выполняется в ответ на определенное событие. Например, обработчик может реагировать на клик по кнопке или изменение текста в поле ввода

10-Запись `this.src` используется для доступа к атрибуту `src` текущего элемента, например, изображения, в контексте обработчика события

11-В JavaScript можно использовать одинарные (') или двойные (") кавычки для строк, главное, чтобы они были согласованы. Также поддерживаются шаблонные строки с использованием обратных кавычек (`)

12-Скрытые блоки могут понадобиться для улучшения пользовательского интерфейса, скрывая ненужную информацию, которая может быть показана по запросу пользователя, например, для всплывающих окон или аккордеонов

13-Скрытому блоку можно присвоить и класс, и идентификатор, чтобы легче стилизовать и находить элемент в коде, а также для применения разных стилей или функциональности

14-Чтобы скрыть или показать блок, нужно изменить свойство `style.display`, устанавливая его значение на "none" для скрытия и "block" или "flex" для показа

15-JavaScript-код выносят в отдельные файлы для повышения читаемости, поддержки и повторного использования кода, а также для уменьшения размера HTML-документа

16-JavaScript-код подключается к веб-странице с помощью тега `<script>`, указывая атрибут `src` с путь к внешнему файлу

17-Для получения ссылки на элемент с известным идентификатором используйте `document.getElementById("идентификатор")`

18-Условный оператор в функции show добавлен для проверки текущего состояния блока (показан или скрыт) перед изменением его видимости

19-Запись `elem.style.display` позволяет взаимодействовать со свойством `display` элемента, управляя его видимостью на странице

20-Команда `return false` в обработчике гиперссылки предотвращает выполнение стандартного действия (перехода по ссылке) и может использоваться для выполнения других действий без перезагрузки страницы

21-Форма — это элемент HTML, предназначенный для сбора пользовательского ввода и отправки данных на сервер для обработки

22-Формы можно использовать без «принимающей» серверной программы, например, для выполнения функционала на стороне клиента с помощью JavaScript (например, валидация данных)

23-Атрибут `name` необходим для идентификации элемента формы при отправке данных, чтобы сервер мог обрабатывать их корректно

24. Браузер отличает кнопку от поля ввода, основываясь на значении атрибута type у тега <input> (например, type="button" и type="text")

25. Текст на кнопке задается с помощью атрибута value, например, input type="button" value="Нажми меня"

26. Для вывода сообщения пользователю в отдельном окне используется функция alert()

#33

1-Хостинг — это сервис для размещения сайтов. Проще всего его представить как удаленный сервер, на котором находятся все файлы сайта, постоянно подключенный к интернету и работающий круглосуточно

2-Размещать сайт на своём домашнем компьютере не имеет смысла, потому что это может привести к проблемам с доступностью, стабильностью, производительностью и безопасностью, а также требует постоянного подключения к интернету и настройки оборудования

3-Бесплатные хостинги часто зарабатывают на рекламе — сайты, пользующиеся услугами хостинга, должны размещать её на своих страницах

4-Тарифный план — стандартная форма коммерческого предложения, в которой указывается перечень возможных услуг и порядок определения их цены

5-Ограничение на трафик сайтов вводится хостингами для избежания монополизации ресурсов одним из клиентов в ущерб остальным

6-Домен 2 уровня регистрируется на частное лицо или компанию, которые являются администратором домена

7-Чтобы связать доменное имя с DNS-серверами, в панели управления доменным именем на сайте регистратора, в разделе редактирования DNS-серверов, введите предоставленные вам адреса

8-Файлы на сервер можно загружать различными способами: через FTP-клиент, с помощью файловых менеджеров, через панель управления хостингом или с использованием командной строки (SSH)
