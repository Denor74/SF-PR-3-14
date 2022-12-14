[< К содержанию](./readme.md)
***
## Основные настройки `git config`

>Команда `git config` — это удобная функция, которая используется для настройки значений конфигурации Git на глобальном и локальном уровнях проекта. Эти уровни конфигурации соответствуют текстовым файлам ***.gitconfig***. При выполнении команды `git config` происходит изменение текстового файла конфигурации.

**Перед началом работы** нужно выполнить некоторые настройки:

```bash
$ git config --global user.name "Your Name" # указать имя, которым будут подписаны коммиты
$ git config --global user.email "e@w.com"  # указать электронную почту, которая будет в описании коммита
```

*Если вы в Windows:*

```
$ git config --global core.autocrlf true # включить преобразование окончаний строк из CRLF в LF
```
Чтобы посмотреть все установленные настройки и узнать где именно они заданы, используйте команду:

```bash
$ git config --list --show-origin   
```
[Подробная документация](https://git-scm.com/docs/git-config) по `git config`
