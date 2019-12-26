---
layout: page
title: Иное использование
permalink: /other-uses/
---

Мы сосредоточили внимание на тайлах, но поскольку OpenStreetMap - это уникальный сервис, который предоставляет свободный доступ к невероятному количеству необработанных картографических данных, с его помощью вы можете сделать любое исследование или даже гео-приложение. Это наиболее распространенные виды использования данных из OpenStreetMap. Полный перечень библиотек, модулей и фреймворков вы можете найти в [OpenStreetMap Wiki](http://wiki.openstreetmap.org/wiki/Frameworks).

## Универсальные инструменты
* [Osmosis](http://wiki.openstreetmap.org/wiki/Osmosis) - универсальное Java-приложение для загрузки данных из OSM в базу данных. Большинство приложений, использующих данные OSM, так или иначе используют Osmosis.
* [Osmium](http://wiki.openstreetmap.org/wiki/Osmium) - гибкий фреймворк, быстро набирающий популярность, который является высоко настраиваемой альтернативой Osmosis.
* [Mapbox Studio](https://www.mapbox.com/mapbox-studio/) - это набор инструментов для создания "векторных тайлов", которые могут быть сгенерированы как на сервере, так и на стороне клиента.
* [Overpass turbo](http://overpass-turbo.eu) - это веб-инструмент анализа и извлечения данных для OpenStreetMap. Он работает через запросы Overpass API и показывает результаты на интерактивной карте. Если вы заходите с территории России, то в настройках в качестве сервера выгрузки необходимо выбрать https://overpass.kumi.systems/api/.

## Сервисы геокодирования
* [Gisgraphy](https://www.gisgraphy.com)  - геокодер с открытым исходным кодом, который предоставляет API / веб-сервис для прямого и обратного геокодирования с автоматическим завершением, интерполяцией, смещением местоположения, поиском поблизости. Все это может быть запущено автономно или в качесте хостинг-решения. Помимо этого, предоставляет некоторые модули импорта для Openstreetmap, Openadresses, Geonames и многое другое.
* [Nominatim](https://nominatim.org) - это программное обеспечение, которое используется для геокодирования на сайте OpenStreetMap. (географическое название <-> широта/долгота).
* [OpenCage](https://opencagedata.com/) предоставляет API для геокодирования, который агрегирует Nominatim и другие сервисы с открытым исходным кодом.
* [OSMNames](https://osmnames.org/) - топонимы из OpenStreetMap. Скачивается. Упорядоченный. С bbox и иерархией. Готов к геокодированию.

## "Движки" и сервисы построения маршрутов
* [OSRM](http://project-osrm.org/) - это быстрый "движок" для маршрутизации, предназначенный для данных OSM.
* [Gosmore](http://sourceforge.net/projects/gosmore/) проверенный временем "движок" для построения маршрутов..
* [Graphhopper](http://graphhopper.com/) - это быстрый движок для маршрутизации на Java.
* [MapQuest Open](http://open.mapquestapi.com/directions/) и [Mapbox](https://www.mapbox.com/directions/) предоставляют публичные API для маршрутизации, которые используют данные OSM.
* К специальным API для маршрутизации можно отнести [CycleStreets](https://www.cyclestreets.net/api/), который строит маршруты для велосипедов (Великобритания и за ее пределами).

## Библиотеки векторных карт (mobile)
* Библиотеки для Android: [Mapbox Android SDK](https://www.mapbox.com/android-sdk/), [mapsforge](http://mapsforge.org/), [Nutiteq Maps SDK](https://developer.nutiteq.com/), [Skobbler Android SDK](http://developer.skobbler.com/) и [Tangram ES](https://github.com/tangrams/tangram-es/).
* Библиотеки для iOS: [Mapbox iOS SDK](https://www.mapbox.com/ios-sdk/), [Nutiteq Maps SDK](https://developer.nutiteq.com/), [Skobbler iOS SDK](http://developer.skobbler.com/) и [Tangram ES](https://github.com/tangrams/tangram-es/).

## Библиотеки векторных карт (Web)
* [Kothic JS](https://github.com/kothic/kothic-js) рендерит данные OSM "на лету" с помощью HTML5, что позволяет обходиться без растровых тайлов.
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/) и [Tangram](http://tangrams.github.io/tangram/) рендерят векторные тайлы из данных OSM с помощью WebGL, что позволяет им увеличить производительность.
