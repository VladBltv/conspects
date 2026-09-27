# Удаленные репозитории
## clone и add origin
__Команды для работы с удаленным репозиторием:__
1) git remote add origin <http url> - Добавить ссылка на удаленный репозиторий
2) git remote -v - Показать подробную инфу о связанных удаленных репозиториях
3) git clone <http url> my-project - Клонировать репозиторий в папку my-project(сама создастся в текущей папке)
4) git clone --depth 1 <http url> - Клонировать репозиторий с 1им коммитом
5) git clone --branch develop --single-branch <https url> - Клонировать репозиторий только с 1ой веткой develop (То что надо скачать 1 ветку указывает --single-branch), а то что нужна именно ветка develop указывает --branch develop.
6) git push origin main - загрузить коммиты с ветки main в удаленный репозиторий под алиасом origin
7) git remote show origin - покажет подробности по удаленному репозиторию с алиасом origin
8) git remote set-name origin origin2 - Переименовать алиас у удаленного репозитория origin
9) git remote set-url origin <new url> - изменить url для удаленного репозитория под алиасом origin
10) git remote rm origin - удалить связь с удаленным репозиторием origin