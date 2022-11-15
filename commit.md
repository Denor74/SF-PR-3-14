[< К содержанию](./readme.md)
***
##  Запись индексированных изменений в репозиторий `git commit`

> `git commit` - это команда для записи индексированных изменений в репозиторий Git. ***Прежде чем создавать очередной коммит, необходимо проиндексировать файлы в рабочей области с помощью команды*** [`git-add`](/add.md "Читать про git add").

Команда `git commit` делает для проекта снимок текущего состояния изменений, добавленных в раздел проиндексированных файлов. Такие подтвержденные снимки состояния можно рассматривать как «безопасные» версии проекта — Git не будет их менять, пока вы явным образом не попросите об этом. Перед выполнением команды git commit необходимо использовать команду git add, чтобы добавить в проект («проиндексировать») изменения, которые будут сохранены в коммите. Эти две команды, `git commit` и `git add`, используются чаще всего.

При создании коммита в репозитории можно добавить однострочное сообщение с помощью **параметра commit с флагом** `-m`. Само сообщение вводится непосредственно после флага, в кавычках.

### Пример использования `git commit`:

```bash
git commit -m "summary about the commit" # Создание снимка текущего состояния изменений, добавленных их в раздел проиндексированных файлов
```

[Подробная документация](https://git-scm.com/docs/git-commit) по `git commit`