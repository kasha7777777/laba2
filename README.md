# 2 лаба — PokéDash

Тематический дашборд Pokémon на HTML, CSS и JavaScript.

## Запуск

Откройте `index.html` в браузере. Для загрузки данных нужен интернет. Установка зависимостей и API-ключи не нужны.

## Возможности

- Выбор двух покемонов и сравнение характеристик.
- Прогноз победителя перед боем.
- Упрощённый автоматический бой, здоровье, журнал ходов и реванш.
- Коллекционные карты выбранного покемона.
- Избранное в localStorage.

## API

- PokéAPI: https://pokeapi.co/api/v2/ — профили и характеристики.
- TCGdex: https://api.tcgdex.net/v2/en/ — коллекционные карты.

## ООП

Базовый класс `Widget`, наследники `ProfileWidget`, `FighterWidget`, `ComparisonWidget`, `CardsWidget`, `FavoritesWidget`, `PredictionWidget`. `ApiClient` загружает и кэширует данные, `BattleEngine` моделирует бой, `Dashboard` связывает виджеты.

## Размещение

Для GitHub Pages выберите Settings → Pages → Deploy from a branch → main → / (root).

## Ограничения

Бой использует здоровье, физическую атаку, защиту и скорость. Типы и приёмы не учитываются. Доступность данных зависит от внешних API. Pokémon принадлежит Nintendo, Game Freak и Creatures.
