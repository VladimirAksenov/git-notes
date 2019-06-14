Git notes readme v2

1. git init - Создание репозитория 
2. git add - Добавление содержимого из выбранной директории 
3. git branch - Список созданных веток, если git branch name - создание ветки
4. git clone - Клонирование репозитория на ПК
5. git remote set-url - Смена текущего репозитория на выбранный (HTTPS / SSH) Берёт значения origin или upstream / Прямая HTTPS или SSH ссылка
6. merge - Скрещивание одной или нескольких версий в одну
7. rebase - Изменение коммитов или истории репозитория
8. fork - Клонирование репозитория с целью изменения проекта без затрагивания оригинала
9. gitignore - Игнорирование выбранного репозитория или формата внутри неё

10.cache clear - Очистка кэша, чтобы работал игнор.
git rm -r --cached .

a. rm - remove command
b. -r will allow recursive removal
c. -cached will only remove file index.
d. . Indicates that all files will be untracked.


a.	Clean - удаление всех созданных в процессе сборки артефактов: .class, .jar
b.	Validate – проверка проекта на правильность
c.	Compile – компилирование 
d.	Test - Тестирование с помощью JUnit тестов
e.	Package - Создание .jar файла
f.	Verify – Проверка результатов теста на правильность
g.	Install - Копирование .jar в локальный репозиторий
h.	Site – Создание документации
i.	Deploy – Завершение, копия проекта в удаленное хранилище 
