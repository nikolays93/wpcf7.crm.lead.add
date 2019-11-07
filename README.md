# Добавление лида в CRM Bitrix24
Запрашивает веб-хук CRM Bitrix24 для создания лида, после отправки сообщения формой contact form 7. (Лид не будет создан, если данные введены неверно.)

### Минимальные требования
- Wordpress (с плагином Contact Forms 7)
- php 5.3

### Как установить/пользоваться
1. Клонировать или скачать проект в папку /wp-content/plugins/wpcf7.crm.lead.add/
2. Изменить константы `BITRIX24_SUBDOMAIN`, `BITRIX24_USER_ID`, `BITRIX24_TOKEN`
3. Изменить значения $posted_fields на свои
4. Активировать как обычный плагин Wordpress

### Альтернативная установка
1. Клонировать или скачать проект в папку /wp-content/mu-plugins/wpcf7.crm.lead.add/
2. Повторить 2, 3 пункты предыдущего раздела

### Дополнительная литература
https://dev.1c-bitrix.ru/community/blogs/chaos/crm-sozdanie-lidov-iz-drugikh-servisov.php
