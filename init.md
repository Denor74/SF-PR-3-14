[< К содержанию](./readme.md)
***
## Инициализация репозитория `git init`

>Команда `git init` создает новый репозиторий Git. С ее помощью можно преобразовать существующий проект без управления версиями в репозиторий Git или инициализировать новый пустой репозиторий. ***Большинство остальных команд Git невозможно использовать без инициализации репозитория, поэтому данная команда обычно выполняется первой в рамках нового проекта***.

Чтобы инициализировать репозиторий, Git создает скрытый каталог с именем ***.git***. В этом каталоге хранятся все объекты и ссылки, которые Git использует и создает как часть истории вашего проекта. 

*Этот скрытый .git каталог - это то, что отделяет обычный каталог от репозитория Git*.

### Общие способы использования и варианты для `git init`

```bash
$ git init # Преобразование текущего каталога в репозиторий Git
git init \<directory\> # Преобразование каталога в текущем пути в репозиторий Git
$ git init --bare # Создайте новый пустой репозиторий (репозиторий, который будет использоваться только как удаленный репозиторий, который не будет содержать активной разработки).
```
[Подробная документация](https://git-scm.com/docs/git-init) по `git init`

