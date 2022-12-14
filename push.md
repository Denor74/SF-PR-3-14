[< К содержанию](./readme.md)
***
## Выгрузка содержимого локального репозитория в удаленный репозиторий. `git push`

> Команда `git push` используется для выгрузки содержимого локального репозитория в удаленный репозиторий. Она позволяет передать коммиты из локального репозитория в удаленный. Эта команда симметрична команде `git fetch`: при извлечении *с помощью fetch коммиты импортируются в локальные ветки*, а при публикации *с помощью push коммиты экспортируются в удаленные ветки*. Настроить удаленные ветки можно с помощью команды [`git remote`](remote.md "Читать о команде git remote")

### Некоторые способы использования `git push`:

```bash
$ git push -u origin master # заливаем все изменения в ветку master

$ git push  # git push по умолчанию. Для этого единожды набираем предыдущую команду с флагом -u После этого можно писать более коротко, так как git запомнил, что пушить надо на сервер origin ветку под именем master
```

[Подробная документация](https://git-scm.com/docs/git-push) по `git push`