# Тестовое задание для Golang разработчика

Тестовое задание для кандидата на должность Golang разработчика.

## Запуск

`go run *.go`

## Описание

Есть внешний сервис, который обрабатывает некие абстрактные объекты батчами. Данный сервис может обрабатывать только
определенное количество элементов `n` в заданный временной интервал `p`. При превышении ограничения, сервис блокирует
последующую обработку на долгое время.

Задача заключается в реализации клиента к данному внешнему сервису, который позволит обрабатывать максимально возможное
количество объектов без блокировки. Приводить реализацию внешнего сервиса **необязательно**!

Определение сервиса можно посмотреть [здесь](./service.go).

## Требования

- решение должно быть в git-репозитории (можно прислать архив или опубликовать на github, gitlab, bitbucket...).

## Пожелания

- документирование кода;
- тесты;
- использование статического анализатора (конфигурацию положить в репозиторий).
