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

## Задание 2-3

Созданы два хоста: `tugushevdf-1` и `tugushevdf-2`.

### Скриншоты

#### Страница хостов (зелёный ZBX)

<img width="1206" height="582" alt="image" src="https://github.com/user-attachments/assets/4918f871-c777-43e3-a44f-dfda07468065" />

#### Привязка шаблонов к хосту tugushevdf-1

<img width="1188" height="695" alt="image" src="https://github.com/user-attachments/assets/7cde79c9-0d64-44af-968c-448508f76346" />

#### Привязка шаблонов к хосту tugushevdf-2

<img width="1188" height="696" alt="image" src="https://github.com/user-attachments/assets/357d81aa-73fc-4f19-8ca6-2ba1adff4a02" />

#### Собираемые данные (Latest data)

<img width="1188" height="694" alt="image" src="https://github.com/user-attachments/assets/5bb926a8-a4e6-47cb-89df-0dd33ef81478" />

### Выполненные действия

- ✅ Создан шаблон `System Monitor - CPU and RAM`
- ✅ Установлен Zabbix Agent на два хоста
- ✅ Добавлены хосты в Zabbix Server
- ✅ К каждому хосту привязан шаблон `Linux by Zabbix agent`
- ✅ К каждому хосту привязан шаблон `System Monitor - CPU and RAM`
- ✅ Данные собираются (зелёный ZBX)
