[< К содержанию](./readme.md)
***
## Основные настройки (git config)


Перед началом работы нужно выполнить некоторые настройки:

```bash
git config --global user.name "Your Name" # указать имя, которым будут подписаны коммиты
git config --global user.email "e@w.com"  # указать электронную почту, которая будет в описании коммита
```

Если вы в Windows:

```
git config --global core.autocrlf true # включить преобразование окончаний строк из CRLF в LF
```
Чтобы посмотреть все установленные настройки и узнать где именно они заданы, используйте команду:

```bash
$ git config --list --show-origin   
```
