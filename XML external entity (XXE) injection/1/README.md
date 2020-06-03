1) Перехватываем запрос от нажатия на кнопку check stock
2) Отправляем запрос в repeater. Отменяем перехват
3) После начала xml добавляем <!DOCTYPE test [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ]>
4) В "ProductId" добавляем &xxe
5) Запуск кода
6) Лаба выполнена
