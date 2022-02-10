# WebFont Montserrat

Пакет для установки веб-шрифта: Montserrat.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-montserrat
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-montserrat": "github:getscope/npm-webfont-montserrat"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Montserrat', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_100-normal.scss";
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-montserrat/src/scss/_all-normal.scss";
```
