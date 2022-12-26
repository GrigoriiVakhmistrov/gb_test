![gitLogo](https://git-scm.com/images/logo@2x.png)

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

# Инструкция по Git

## Создание репозитория

Для создания репозитория необходимо:

- установить Git
- установить IDE

- создать пустую папку
- открыть папку в IDE
- открыть терминал
- инициализировать репозиторий командой `git init`

## Команды для работы с Git
Добаление отслеживания файлов
- `git add --all`, `git add -A` - добавление всех файлов
- `git add <file_name.ext>` - добавление определенного файла

Фиксация текущего содержания файла
- `git commit -m "commit mesage"`

Просмотр журнала событий
- `git log` - отобразить коммиты, которые были выполнены ранее
- `git log --graph` - добавляет ASCII-граф, показывающий историю ветвлений и слияний.


Переход к определенному коммиту или ветке
- `git checkout <id_commit>`
- `git checkout <name_branch>`

Вывод изменений до коммита
- `git diff`

Клонирование репозитория
- `git clone <repo_URL>`

Выгрузить актуальную версию удаленного репозитория
- `git pull`

Оаправить изменеия в локальном репозитории в удаленный репозиторий
- `git push`

---

[Официальный сайт](https://git-scm.com/)
