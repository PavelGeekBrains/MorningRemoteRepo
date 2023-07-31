# My first remote repository

# GIT commandes
_Homework 3_
## Настройка репозитория

### Инициализация нового репозитория: git init

Для создания нового репозитория используется команда git init. Команду git init выполняют только один раз для первоначальной настройки нового репозитория. Выполнение команды приведет к созданию нового подкаталога .git в вашем рабочем каталоге. Кроме того, будет создана новая главная ветка.

* git init – инициализация локального репозитория


## Сохранение изменений

### Порядок действий

Команды git add и git commit составляют основу рабочего процесса Git. Эти две команды должен изучить и понимать каждый пользователь Git, независимо от модели совместной работы, принятой в его команде. Эти команды используются для записи версий проекта в историю репозитория.

Работа над проектом ведется по стандартной схеме «редактирование — индексирование — коммит». Сначала вы редактируете файлы в рабочем каталоге. Когда вы будете готовы сохранить копию текущего состояния проекта, вы индексируете изменения командой git add. Затем вы вызываете команду git commit, которая добавляет проиндексированный снимок состояния в историю проекта. Для отмены коммита или проиндексированного снимка состояния используется команда git reset.



## Проверка репозитория

Команда git status отображает состояние рабочего каталога и раздела проиндексированных файлов. С ее помощью можно проверить индексацию изменений и увидеть файлы, которые не отслеживаются Git. Информация об истории коммитов проекта не отображается при выводе данных о состоянии. Для этого используется команда git log.

## Отмена изменений

Мы рассмотрели множество общих стратегий отмены изменений в Git. Важно помнить, что отменить изменения в проекте Git можно несколькими способами. Кроме того, здесь были затронуты и более сложные темы, которые подробно рассматриваются на страницах, посвященных соответствующим командам Git. Наиболее часто используемые инструменты для отмены — это команды git checkout, git revert и git reset. Вот несколько ключевых моментов, о которых следует помнить.

Обычно после коммита внесенные изменения отменить невозможно
Используйте git checkout для переходов и просмотра истории коммитов
Команда git revert — лучший инструмент для отмены общих публичных изменений.
Команду git reset лучше всего использовать для отмены локальных частных изменений.








## Git useful commands

* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git checkout – переход от одного коммита к другому
* git checkout master – вернуться к актуальному состоянию и продолжить работу
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом



THE END


Changed from Vasileva



