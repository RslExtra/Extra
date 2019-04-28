# Extra
Дополнительные библиотеки для макроязыка RSL.

## Установка

1) Клонируем или сохраняем репозиторий на локальной машине.
2) Папку Extra перемещаем на сервер RS-BANK в папку /Mac/
3) Импортируем необходимые библиотеки по отдельности или всю библиотеку целиком строкой
`import "..\\Mac\\Extra\\Extra.mac";`

## Состав библиотеки

1) Collections - библиотека коллекций.
2) StreamApi - Stream для RSL.
3) Lambda - лямбда-выражения.
4) Utils - полезные утилиты для работы с массивами и строками.
5) Forms - часть библиотеки UI элементов для RS-BANK 5.
6) RUnit - юнит тесты на языке RSL.
7) LogR  - удобное логирование.

- Примеры использования в папке `/_Samples/`.
- Юнит тесты в папке `/_Tests/`

Документация в репозитории https://github.com/RslExtra/RslExtra.github.io
Для работы с документацией внутри сети необходимо закинуть папку с документацией на любой веб-сервер (без PHP, СУБД и т.д.).

Также документация доступна по адресу https://rslextra.github.io/