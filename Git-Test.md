# Инструкция по работе с Git
## Имя и адрес
1. git config --global user.name "*вводим имя*"
2. git config --global user.email "*вводим адрес*"
## Добавление файла
- git add  - добавление файла
- git commit -m "*комментарий*"
## Посмотреть историю 
git log - посмотреть историю ветки

**Важно!** 
Чтобы выйти из блокировки нужно нажать q
## Переход между версиями
git checkout *первые 4 символа версии*
### чтобы вернуться к последней версии нужно ввести
git checkout main
## Посмотреть текущее состояние
git status - посмотреть текущее состояние 

### *Немного о git status*
Команда git status отображает все файлы. У файлов есть 4 состояния:
1. Неотслеживаемый (untracked) — находится в рабочей директории, но нет ни одной версии в HEAD или в области подготовленных файлов (Git не знает о файле).
2. Изменён (modified) — в рабочей директории есть более новая версия по сравнению с хранящейся в HEAD или в области подготовленных файлов (изменения не находятся в следующем коммите).
3. Подготовлен (staged) — в рабочей директории и области подготовленных файлов есть более новая версия по сравнению с хранящейся в HEAD (готов к коммиту).
4. Без изменений — одна версия файла во всех разделах, т. е. в последнем коммите содержится актуальная версия.

## Удаленные репозитории
