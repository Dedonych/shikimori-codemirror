### Темы для Шикимори (CodeMirror)

Для поиска тем, зайдите на [сайт Codemirror](https://codemirror.net/5/demo/theme.html) и вставьте в консоль данные строчки:

```js
(async function(){
    await import("https://cdnjs.cloudflare.com/ajax/libs/codemirror/6.65.7/mode/css/css.min.js");
    editor.setOption("mode","css");
    editor.setValue(`div,\n.class,\n#id,\n[href="some_href"]{\n\tdisplay: flex;\n\tcolor: red;\n\tbackground: #1bb1b1;\n\tgap:var(--gap);\n}\n`)
})()
```
Дальше, выбирайте себе тему какая понравится, и, по названию ищите в папке `src` и вставляйте в свой редактор:

```css
@import ("https://raw.githubusercontent.com/Dedonych/shikimori-CodeMirror/master/src/название-темы.css");
```