# Памятка по git и его основнные команды

## I. git command
1. git init- иниилизация репозитория 
2. git status- текущий статус гит
3. git add- добавления изменений в репозиторий 
4. git commit -m "massage"- коментарий к текущему изменению 
5. git log- показыввает коммиты 
6. git branch- создание новой ветки 
7. git merge- слияние веток 
8. git checkout- переход по веткам 
9. git diff- разница между последеним коммитом
## II. git command commit 
1. git rebase- Второй способ объединения изменений в ветках - это rebasing. При ребейзе Git по сути копирует набор коммитов и переносит их в другое место
2. git cherry-pick-Это очень простой и прямолинейный способ сказать, что ты хочешь копировать несколько коммитов на место, где сейчас находишься
3. git difftool- Команда git difftool просто запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff
4. git reset-Команда git reset, как можно догадаться из названия, используется в основном для отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса. Также эта команда может изменить файлы в рабочем каталоге при использовании параметра --hard, что может привести к потере наработок при неправильном использовании, так что убедитесь в серьёзности своих намерений прежде чем использовать его.
5. git reset-Команда git reset, как можно догадаться из названия, используется в основном для отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса. Также эта команда может изменить файлы в рабочем каталоге при использовании параметра --hard, что может привести к потере наработок при неправильном использовании, так что убедитесь в серьёзности своих намерений прежде чем использовать его.
6. git mv-Команда git mv — это всего лишь удобный способ переместить файл, а затем выполнить git add для нового файла и git rm для старого
7. git clean-Команда git clean используется для удаления мусора из рабочего каталога. Это могут быть результаты сборки проекта или файлы конфликтов слияний.
8. cd [papka]- команда позволяет пееремещаться в папках внутри репозитория
9. git add .- добавляет изменения на все файлы в репозиторий