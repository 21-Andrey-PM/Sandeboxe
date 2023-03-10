## Установка python
На этой странице вы можете скачать python для Windows. (https://www.python.org/downloads/windows/)

![image](https://user-images.githubusercontent.com/125145037/224363550-7c01ad22-434f-48e8-9159-a30a5ed9cbde.png)

Нажмите на ссылку, которая начинается словами “Последний выпуск Python 3…” и попадете на страницу последней версии Python3.

Внизу страницы версии ссылки на скачивание установщиков. Есть возможность скачать python под 64-битную и 32-битную Windows.

![image](https://user-images.githubusercontent.com/125145037/224364226-d05f6bd9-8104-438f-8eea-7cef43b167d8.png)

Скачайте и запустите установщик Python 3, он называется “python-3.****.exe”

На первом экране обязательно отметьте пункт “Add python.exe to PATH” и нажмите “Install Now”

![image](https://user-images.githubusercontent.com/125145037/224364939-b582e7a0-e120-43a6-95c9-2d373a089d22.png)

## Как проверить установился ли python

1. Запустите командую строку
2. Введите `python`

В результате командная строка выведет версию python, которая установлена в системе.

![image](https://user-images.githubusercontent.com/125145037/224366689-ed385299-9284-4bdc-8b6e-bdd20513fa87.png)

Также рекомендую на всякий случай проверить наличие “pip”

Для этого в командной строке наберите `pip --version`

![image](https://user-images.githubusercontent.com/125145037/224366908-b5b0e783-5d0d-426d-b9bd-0a33e5c8e5de.png)

Если выводит ошибку, то это означает, что вы вначале не нажали галочку на “Add python.exe to PATH”

Что бы это исправить рекомендую зайти на этот сайт(https://okdk.ru/kak-dobavit-python-v-peremennuju-windows-path/)

Там подробно представлены различные способы решения этой проблемы.

## Создание и активация виртуального окружения

Для создания виртуального окружения в командной строке набираем команду `python -m venv _имя окружения_`.

![image](https://user-images.githubusercontent.com/125145037/224368910-fde8f1aa-2f53-483d-b407-dc2d69efd18c.png)

Для активации используем команду `_имя окружения_\Scripts\activate`

![image](https://user-images.githubusercontent.com/125145037/224371241-b0ac93f0-8a93-433d-9b3a-23dd94b69658.png)

В `Windows PowerShell` может вылезти ошибка “Невозможно загрузить файл … так как выполнение сценариев отключено в этой системе”.

Если такое произошло, то следует выполнить следующие действия:

- Запускаем терминал от админа.
- Пишем и запускаем: `Set-ExecutionPolicy RemoteSigned`

## Использование pre-commit

