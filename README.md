# Отчет по лабораторной работе №6
### Еремина К.О.  Группа № 4316

---

## Цель лабораторной работы: 
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 

## 1. Создание аккаунта на GitHub
Аккаунт успешно создан на [GitHub] и настроен клиент git.
![Скриншот настройки клиента git](screenshots/1.jpg)

## 2. Копирование репозитория (Fork)
Сделана копия в личное хранилище из оригинального репозитория
https://github.com/Kurtyanik/LR6/ с помощью кнопки **Fork**. 
![Скриншот форка репозитория](screenshots/2.jpg)

## 3. Клонирование репозитория и пулл изменений 

![Клонирование и пулл] (screenshots/3.jpg)

# 4. Вывод истории коммитов для каждой из веток

- Так как по умолчанию ветка всего одна - то история только для  ветки master.
![Вывод истории коммитов](screenshots/4.jpg)

## 5. Проверка ветки с помощью git status
 
- При проверке видим, что незафиксированных файлов нет.

![Проверка ветки](screenshots/5.jpg)

## 6. Создание и разрешение конфликта при слиянии веток

- В изначальном репозиторие была всего одна ветка, чего недостаточно, для конфликтной ситуаци, поэтому создём ещё одну ветку на которой создаём файл file2.txt и пишем в нём "hello".

![Создание и разрешение конфликта](screenshots/6.jpg)

- Далее создаём такой же файл file2.txt в master и пишем в нем "goodbye", потом выполняем слияние и получаем конфликт.

![Создание и разрешение конфликта](screenshots/7.jpg)

- Конфликт внутри файла выглядит так:
  
![Создание и разрешение конфликта](screenshots/8.jpg)

- Конфлик решён, путём самостоятельного внесения изменений в файл и сохранения изменений.
  
![Создание и разрешение конфликта](screenshots/9.jpg)

## 7. Фиксация изменений после разрешения конфликта и удаление ненужной ветки

![Фиксация изменений и удаление ветки](screenshots/10.jpg)

## 8. Откат последнего коммита

![Откат коммита](screenshots/11.jpg)

## 9. Использованные команды
- git clone https://github.com/username/repo.git - Клонирование удалённого репозитория на локальный носитель
- git checkout -b new-branch - Создание и переход на созданную ветку
- git add . - Фиксация файлов (в данной вариации всех незафиксированных файлов)
- git add FileName - Фиксация файла
- git commit -m "Added new feature" - Создание комментария 
- git push origin new-branch - отправка коммитов в удалённый репозиторий

## 10. Получение истории операций в форматированном виде

![Получение истории операций](screenshots/12.png)

# Вывод:
В ходе выполнения лабораторной работы я освоила основные команды Git и GitHub, что существенно упростило управление версиями и совместную работу над проектами. Практика разрешения конфликтов при слиянии веток укрепила мои навыки работы с потенциальными проблемными ситуациями. Написание отчета в формате Markdown показало важность документирования процесса разработки.