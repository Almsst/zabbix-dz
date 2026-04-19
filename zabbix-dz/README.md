# Домашнее задание Zabbix

## Задание 1

Создан шаблон `System Monitor - CPU and RAM` для мониторинга загрузки CPU и RAM хоста.

### Скриншот

![Задание 1](task1.png)

### Скриншоты

#### 1. Шаблон с элементами данных (Items)

![Items](items.png)

*На скриншоте показаны два item'а:*
- `CPU load in percent` с ключом `system.cpu.util[,,user]`
- `RAM usage in percent` с ключом `vm.memory.size[pused]`

#### 2. Собираемые данные (Latest data)

![Dashboard](dashboard.png)

*На скриншоте видно, что данные успешно собираются:*
- Загрузка CPU: ~4.5%
- Загрузка RAM: ~63.8%
### Статус выполнения

- ✅ Шаблон создан
- ✅ Item для CPU добавлен
- ✅ Item для RAM добавлен
- ✅ Шаблон привязан к хосту Zabbix server
- ✅ Данные собираются успешно
