# Домашнее задание Zabbix

## Задание 1

Создан шаблон `System Monitor - CPU and RAM` для мониторинга загрузки CPU и RAM хоста.

### Скриншоты

#### 1. Шаблон с элементами данных (Items)

<img width="993" height="470" alt="image" src="https://github.com/user-attachments/assets/d85a103f-5578-4b86-a422-af663e6dc305" />

*На скриншоте показаны два item'а:*
- `CPU load in percent` с ключом `system.cpu.util[,,user]`
- `RAM usage in percent` с ключом `vm.memory.size[pused]`

#### 2. Собираемые данные (Latest data)

<img width="1198" height="619" alt="image" src="https://github.com/user-attachments/assets/8b8b5413-cdee-4e8a-9b87-389da6b13a9b" />

### Статус выполнения

- ✅ Шаблон создан
- ✅ Item для CPU добавлен
- ✅ Item для RAM добавлен
- ✅ Шаблон привязан к хосту Zabbix server
- ✅ Данные собираются успешно
