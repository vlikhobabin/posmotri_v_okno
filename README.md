# Проектная работа «Посмотри в окно»
Спринт 6/36: Спринт 2 → Тема 14/15: Проект 2: «Посмотри в окно»
https://github.com/vlikhobabin/posmotri_v_okno
## Описание проекта
В этой проектной работе нужно было написать CSS для работающего приложения. В стартовом репозитории было получено много готовых файлов: вся HTML-разметку, CSS для компонентов прелоадера и вывода ошибки, файлы шрифтов и стили для них, файл со скриптом с описанной логикой работы приложения. Моя задача была — дополнить файл style.css так, чтобы интерфейс приложения соответствовал макету.
## Функциональность скрипта (предоставлен в готовом виде)
* При загрузке страницы скрипт получает данные из внешнего источника, отрисовывает пять карточек с видео и кнопку, чтобы подгрузить дополнительные карточки. 
* Подставляет адрес первого из загруженных роликов в тег <video> внутри крупного блока на странице.
* Отслеживает клик по карточкам и переключает текущее видео в зависимости от выбранной карточки.
* Следит за отправкой формы. После отправки он ищет в базе данных совпадения по введённым параметрам и перерисовывает страницу с данными, полученными из нового запроса.

В случае ошибок на место блока с видео подставляется блок с сообщением об ошибке. А пока идёт поиск, в блоки с видео и карточками подставляются прелоадеры, отображающие анимацию процесса загрузки.

При работе над вёрсткой мне нужно было сохранить эту функциональность и не навредить ей. Поэтому изменялся только CSS, не менялись уже написанные имена классов, действий с HTML-кодом не было.
