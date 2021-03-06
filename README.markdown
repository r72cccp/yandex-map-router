Тестовое задание - редактор маршрута на карте
=============================================

## Что это

Редактор маршрутов — одностраничное приложение, в котором пользователь в интерактивном режиме может создавать на карте
маршрут, указывая начальную, конечную и промежуточные точки движения. Для каждой точки маршрута можно посмотреть ее адрес

## Как пользоваться

0. по [ссылке](https://yandex-map-router.herokuapp.com/) доступно работающее приложение.

1. Тыкать в карту (одиночный клик левой кнопкой мыши), добавляя таким образом новые точки в маршрут

2. Слева будут появляться точки - их можно удалить с помощью крестика

3. Так же можно поменять порядок следования точек маршрута, перетягивая пункты списка вверх или вниз.

## Локальная установка

```bash
git clone git@github.com:r72cccp/yandex-map-router.git
cd yandex-map-router
yarn install
bin/start_dev
```

## Работающий код

[Деплой на Heroku](https://yandex-map-router.herokuapp.com/)

![Демо gif](guide/demo.gif)]

## Тестирование

Запуск Selenium тестов

```bash
cd tests/selenium
cucumber
```
