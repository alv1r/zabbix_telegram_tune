
# Настройка уведомлений Zabbix в Telegram 
Модифицированный шаблон для оповещений в Telegram. Проверено на Zabbix 5.2

Для удобства визуальной обработки сообщений от Zabbix сервера, в зависимости от важности проблем им присвоены определенные emoji, а ключевые части сообщений выделены ****жирным****
 
За основу взят [официальный шаблон](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse/templates/media/telegram/media_telegram.yaml), настройки же скрипта взяты у [dangkiena3](https://hoctapit.com/zabbix-5-0-telegram-emoji-by-severity-support/).

# Установка

Заходим на свой zabbix. 
Administration -> Media types. 
Удаляем Telegram и импортируем zbx_telegram.yaml

Сообщения будут приходить примерно такого вида:


