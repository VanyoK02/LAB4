# LAB4
Репозиторий для лабораторной работы номер 4. Цель работы: изучить основы работы с системой управления версиями Git, освоить процесс создания репозитория. Выполнил Мелехов Иван Сергеевич, студент группы мИИВТ-241

git init - создаёт в папке гит репозиторий
git config user.name - создаёт имя автора изменений (локальные, на уровне проекта)
git config user.email - создаёт почту автора изменений (локальные, на уровне проекта)
git config --global user.name - создаёт имя автора изменений (глобальные, на уровне пользователя)
git config --global user.email - создаёт почту автора изменений (глобальные, на уровне пользователя)
cat .git/config - просмотр директории гит
git config --unset user.name - удаляет локальные параметры (имя пользователя)
git config --unset user.email - удаляет локальные параметры (почту пользователя)
git config --list - выводит список значени параметров конфигураций
git config --global alias.c config - создает псевдоним для команды (git config)
git config --global core.editor - используется для настройки текстового редактора, который будет использоваться по умолчанию для редактирования сообщений коммитов
git config -h - выводит все команды config и их описание
git help config - выводит подробную информацию о команде config
git statusv - выводит подробную информацию о команде config
git add "название файла" - проиндексирование файла (отслеживание)
git commit - добавление файла в репозиторий