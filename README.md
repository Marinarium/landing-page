# landing-page
Test

## Gulp
- `gulp build` - собрать проект
- `gulp dev` - сборка проекта в режиме разработки (watch + browserSync)
- `gulp lint` - проверка js 
- `gulp styles` - сборка/обновление только стилевых файлов
- `gulp images` - оптимизация картинок
- `gulp clean` - очистка public

## Структура проекта
### Base
Содержит глобальные правила "box-sizing", сброс CSS или стили для печати - всё, что должно быть задано в самом начале CSS, но еще не зависит от конкретного проекта.
- _reset.scss 
- _typography.scss   

### Abstracts
Здесь мы определяем переменные для шрифта, цветов, отступов, медиа-запросов и всего остального, что будем использовать при вёрстке.
- _variables.scss    
- _functions.scss    
- _mixins.scss      

### Components
Компоненты интерфейса.
- _button.scss
- _link.scss
- _menu.scss

## HTML
### Примеры:
#### Блоки
```html
<header class="header"></header>
<form class="search-form"></form>
<div class="logo"></div>
```
#### Элементы
```html
<form class="search-form">
    <!-- Элемент `input` блока `search-form` -->
    <input class="search-form__input">
    <!-- Элемент `button` блока `search-form` -->
    <button class="search-form__button">Найти</button>
</form>
```
#### Модификаторы
```html
<button class="search-form__button--sm">Найти</button>

```
