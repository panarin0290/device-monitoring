Продолжение реализации artem-projects/device-monitoring
Внесены свои изменения.
1. Добавлено:
1.1 Меню:
1.1.1 Главная - список всех устройств
1.1.2 Объекты - выборка по объектам
1.1.2 Действия:
1.1.2.1 Добавление устройств
1.1.2.2 Добавление группы устройств
1.1.2.3 Удаление устройств
1.1.2.4 Удаление группы устройств
1.2 Дописание маршрутизации для страниц
1.3 Тестовое добавление сбора информации с устройств по SNMP
1.4 Внесение изменений в класс DeviceDiscovery

Исправить: 
Решить глюк при добалении групп или устройств(сейчас реализованы устройства и группы через файл .json) - необходимо, либо изменить логику работы обновления даты последней активности, либо перенести в базу, либо другой вариант.

Дописать:
Логику работы сбора информации по SNMP и вывод этой информации.

