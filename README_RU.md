# PassGenius
PassGenius - это инструмент командной строки для генерации и сохранения надежных паролей. Программа не хранит пароли, а генерирует их на основе мастер-пароля и URL-адреса сервиса.


## Установка
Склонируйте репозиторий на свою локальную машину:

```shell
git clone https://github.com/TE1ch0st/passgenius.git
```
## Использование
PassGenius может быть использован для генерации безопасных паролей, а также позволяет заменять скомпрометированные пароли на новые, если это необходимо.

---

# CLI Версия
## Вызов справки
```shell
python3 PassGenius.py --help

Список команд
        -h --help : Вызов справки
        gen : Инструмент генерации пароля
         rep (replace) : Инструмент для смены пароля

    -----------------------------
    gen (generate) [flags] - Генерация пароля
         -d --Domain [url] :  URL адрес сайта
         -s --Secret [password] : Мастер пароль для генерации
         -l --Len [number] : Длина пароля (По умолчанию: 25)

    -----------------------------
    rep (replace) [flag] - Замена пароля
         -p --Password [you_password] : Пароль требующий замены
```

---

# WEB Версия
<div align="center">
    <img src="https://raw.githubusercontent.com/TE1ch0st/passgenius/main/assets/web.png" width="300">
</div>

---

# DESKTOP Версия

<div align="center">
    <img src="https://raw.githubusercontent.com/TE1ch0st/passgenius/main/assets/win.png" width="300">
</div>
___

## Лицензия
Licensed under the Apache License, Version 2.0

---
Copyright © 2023 TE1ch0st. All rights reserved.