# Software-Engineering-2021
Peter the Great St. Petersburg Polytechnic University: Software Engineering course 2021

Feel free to ask all your questions on the course's telegram channel.

## 80101

- Фам Тхи Тхань Бинь
    - HW1:
        * Status: Done (Nov 13)
        * Notes:
            - Наличие ветки `main` говорит о `git-flow`, но никакого кода в `main` я не вижу. Нужно доделать работу (используя `release/` ветку).
            - Для работы над фичами, стоит использовать ветки с префиксом `feature/`
            - Необходимо исправить `.gitconfig`
            - Декомпозиция задач есть, но это декомпозиция с точки зрения инженера. Бизнесу из описания задачи должно быть понятно, какую пользу несёт эта фича!
            - Линковка задач и коммитов сделана неожиданно))) Я предполагал обратное, т.к. в комментарии к коммиту указывать номер проблемы, которая решается этим коммитом.
-

## 80202

- Кобыжев Александр
    - https://github.com/alexnevskiy/BitcoinWatcher
    - HW1:
        * Status: Done (Nov 10)
        * Notes:
            - Для работы над фичами, стоит использовать ветки с префиксом `feature/`
            - Ветка `develop` не мерджится прямо в `master`, для этого есть `release/`. В этой же ветке проставляются номера версий для артефактов.
            - Прямые коммиты в `master` не допустимы; каждый коммит в `master` это релиз новой версии продукта!
            - Часть коммитов (из web-интерфейса GitHub) сделана от имени одного пользователя, а другая часть (с рабочей станции) от имени другого. Проблема в `.gitconfig`. С этим нужно разобраться для HW2.
            - Мне нравится как оформлен `README.md`
            - Работа с `DE`, конечно, не то, для чего создавался `Docker`, то это вполне решаемая задача заставить уведомления работать из контейнера.
            - Проигнорировано требование декомпозиции задачи на `issues` и линковка коммитов с задачами.
            - Бедные описания к коммитам, они не отвечают на вопрос "зачем?".
    - HW2:
- Сухачев Никита
    - https://github.com/SukhachevN/Software-Engineering-2021
    - HW1:
        * Status: Done (Nov 13)
        * Notes:
            - Всё те же замечания, что я писал Фам Тхи Тхань Бинь: нужен коммит в `main` (раз он есть), префикс для `feature/` веток, настроить `.gitconfig`
            - В задачах заметил "Рефакторинг". Такие задачи плохо продаются бизнесу, т.к. не несут коммерческой ценности. На эту тему можно почитать Фаулера, он описывает принцип бойскаутов для решения таких ситуаций.
            - Не стоит миксовать русский и английский языки при комментировании коммитов.

## 80203

- Tarasenko Nikita
    - https://github.com/GetRhymes/ConverterXML
    - HW1:
        * Status: Done (Nov 13)
        * Notes:
            - Ветки `develop` и `master` друг к другу не ходят, для этого есть `release` и `hotfix`
            - Видимо вначале были проблемы с `.gitconfig`
            - Служебные папки (`.idea`) тоже принято прятать за `.gitignore`
-
-

## 80201

-
-
-
