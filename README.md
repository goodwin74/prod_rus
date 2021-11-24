# База продуктов SQL и JSON
База продуктов 2021 (фрукты, овощи, ягоды и тд) на русском языке с данными о белках, жирах, углеводов и калорийности (килоколорий)

Вы можете загрузить прямо в базу SQL файл, подгружать JSON или использовать JS версию.
## CDN для JS версии
https://cdn.jsdelivr.net/gh/goodwin74/prod_rus/products.min.js

Просто подключите JS к своему проекту в нужный момент или при запуске.
### Ванильный JS
```
var prodjs = document.createElement('script');
prodjs.setAttribute('src','https://cdn.jsdelivr.net/gh/goodwin74/prod_rus/products.min.js');
document.head.appendChild(prodjs);
```
### JQuery
```
$.getScript("https://cdn.jsdelivr.net/gh/goodwin74/prod_rus/products.min.js", function(){
    console.log("Скрипт загружен");
});
```

Сказать спасибо > <a href="https://yoomoney.ru/to/41001412274855">Донат</a>

![donate](https://user-images.githubusercontent.com/15101984/143142406-baacd3e3-e4f9-4a2a-b6bc-466b49181307.gif)
