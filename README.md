## Примеры кода БЭМ

### 1. Выбор языков

```html
<div class="box-lang">
  <ul class="list-lang">
    <li class="list-lang__item active">
      <a class="list-lang__link" href="#">Рус</a>
    </li>
    <li class="list-lang__item">
      <a class="list-lang__link" href="#">укр</a>
    </li>
  </ul>
</div> 
```

### 2. Элементы форм

```html
<div class="box-form">
  <form>
    <div class="box-field">
      <label for="" class="box-field__label"></label>
      <div class="box-field__input">
        <input type="text" class="form-control" placeholder="Имя">
      </div>
    </div>
    <div class="box-field">
      <label for="" class="box-field__label"></label>
      <div class="box-field__input">
        <select>
          <option>name_1</option>
          <option>name_2</option>
        </select>
      </div>
    </div>
  </form>
</div>
```
<br>
В текстовых полях параметр type может принимать следующие значения:
text, password, email, number, search, tel, url

#### Списки с радио кнопками: 

```html
<ul class="list-radio">
  <li class="list-radio__item">
    <label class="list-radio__label">
      <input type="radio" name="name_1">
      <span class="label-text">Name_1</span>
    </label>
  </li>
  <li class="list-radio__item">
    <label class="list-radio__label">
      <input type="radio" name="name_1">
      <span class="label-text">Name_2</span>
    </label>
  </li>
</ul>
```

#### Списки с чекбоксами:

```html
<ul class="list-check">
  <li class="list-check__item">
    <label class="list-check__label">
      <input type="checkbox" name="check_1">
      <span class="label-text">Name_1</span>
    </label>
  </li>
  <li class="list- check__item">
    <label class="list-check__label">
      <input type="radio" name="check_2">
      <span class="label-text">Name_2</span>
    </label>
 </li>
</ul> 
```

### 3.Основное меню: 

```html
<nav class="main-nav">
  <ul class="main-nav-list">
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link"></a></li>
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link"></a></li>
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link"></a></li>
  </ul>
</nav>
```

### 4. Кнопки:

Кнопкам задается класс .button изменения цветов фонов, любых параметров  - дописывается модификатором, к примеру .button_primary, .button_default...
```css
.button{
  display: inline-block;
  vertical-align: top;
  padding: 16px 30px 0 30px;
  height: 52px;
  border-radius: 26px;
  position: relative;
  font-size: 16px;
  line-height: 18px;
  letter-spacing: 0.5px;
  color: #0f3755;
  border: 1px solid #ffc601;
  background: #ffc601;
  transition: all 0.2s linear;
  text-align: center;
}
.button:hover{
  border-color:#0f3755;
  background: #0f3755;
  color: #FFF;
}
button.button, input.button{ padding-top: 0px!important;}
.button_small{
  height:34px;
  padding: 9px 23px 0 23px;
  font-size: 14px;
  line-height: 16px;
}

```

### 5. FAQ: 

```html
<div class="box-faq">
  <a href="#" class="box-faq__link-all">Показать/Скрыть все</a>
  <ul class="list-faq">
    <li class="list-faq__item">
      <a href="#" class="list-faq__link">question?</a>
      <div class="list-faq__answer">
        <p>Ответ</p>
      </div>
    </li>
  </ul>
</div>
```

### 6. Статьи:

```html
<div class="box-article">
  <article class="box-article__item">
    <h3><a href="#"></a></h3>
  </article>
  <article class="box-article__item">
    <h3><a href="#"></a></h3>
  </article>
</div>
``` 

### 7. Новости:

```html
<div class="box-news">
  <article class="box-news__item">
    <h3><a href="#"></a></h3>
  </article>
  <article class="box-news__item">
    <h3><a href="#"></a></h3>
  </article>
</div>
``` 

### 8. Список продуктов:

```html
<ul class="products-list">
  <li class="products-list__item">
    <div class="products-list__cont">
      <div class="products-list__logo">
        <a href="#"><img src="img/logo_1.png" alt=""></a>
      </div>
      <div class="description-product">
        ...
      </div>
    </div>
  </li>
</ul>
``` 

### 9. Хлебные крошки: 

```html
<div class="box-bread-crumbs">
  <ul class="bread-crumbs">
    <li class="bread-crambs__item">
      <a href="#" class="bread-crambs__link">Главная</a>
    </li>
    <li class="bread-crambs__item">Оплата и доставка</li>
  </ul>
</div>
``` 

### 10. Пагинация: 

```html
<div class="box-paging">
  <ul class="paging-list">
    <li class="paging-list__item paging-prev">
      <a href="#" class="paging-list__link">
        <span class="arrow-paging"></span>
      </a>
    </li>
    <li class="paging-list__item active">
      <a href="#" class="paging-list__link">1</a>
    </li>
    <li class="paging-list__item">
      <a href="#" class="paging-list__link">2</a>
    </li>               	                                     	
    <li class="paging-list__item paging-next">
      <a href="#" class="paging-list__link">
        <span class="arrow-paging"></span>
      </a>
    </li>
  </ul>
</div>
``` 

### 11. Таблицы (если верстаются без использования table):

```html
<ul class="table-list">
  <li class="table-list__item">
    <div class="col col_1">...</div>
    <div class="col col_2">...</div>
    <div class="col col_3">...</div>
  </li>
  <li class="table-list__item">
    <div class="col col_1">...</div>
    <div class="col col_2">...</div>
    <div class="col col_3">...</div>
  </li>
</ul>
``` 
в стилях колонки прописываются либо display:table-cell (тогда li это display:table-row, а ul - display:table), либо display:inline-block. либо делаем на flex<br>

### 12. Попапы:

```html
<a href="#win_1" class="fancybox">открывается первое окно</a>
<a href="#win_2" class="fancybox">открывается второе окно</a>
``` 
Попапы в коде ставятся перед закрытием основного дива main-wrapper
```html
<div class="popup">
  <div class="window-open" id="win_1">
    <div class="window-open-cont">
      ...
    </div>
  </div>
  <div class="window-open" id="win_2">
    <div class="window-open-cont">
      ...
    </div>
  </div>
</div>
``` 
Скрываются попапы классом .popup без использования display:none;
```css
.popup{
  position:absolute;
  left:-9999px;top:-9999px;
  opacity:0;
}
.window-open {
  width:1345px;max-width:100%;
  background:#FFF;
  position:relative;
  box-shadow:0 0 7px 0 rgba(0,0,0,0.5);
  padding:35px;
}
```

### 13. Табы: 

```html
<div class="tab-wrap">
  <ul class="nav-tab-list tabs">
    <li class="nav-tab-list__item active">
      <a href="#tab_1" class="nav-tab-list__link">таб_1</a>
    </li>
    <li class="nav-tab-list__item">
      <a href="#tab_2" class="nav-tab-list__link">таб_2</a>
    </li>
  </ul>
  <div class="box-tab-cont">
    <div class="tab-cont" id="tab_1">...</div>
    <div class="tab-cont hide-tab" id="tab_2">...</div>
  </div>
</div>
```
Неактивный таб скрывается стилями без использования display:none;
```css
.box-tab-cont{
  position: relative;
}
.hide-tab{
  position: absolute;
  left: 0;top: 0;
  height:0; width:0;
  overflow:hidden;
  z-index: -1;
  opacity: 0;
}
```
Скрипт для табов
```js
$('.tabs li a').click(function() {
  $(this).parents('.tab-wrap').find('.tab-cont').addClass('hide-tab');
  $(this).parent().siblings().removeClass('active');
  var id = $(this).attr('href');
  $(id).removeClass('hide-tab');
  $(this).parent().addClass('active');
  return false;
});
```

## Примеры кода полезных скриптов:

#### 1. Если нужно зафиксировать какую-то плашку, панель, сайдбар - это делается без дополнительных плагинов: 

```js
if($('.fixed-block').length){
  var offset_this = $('.fixed-block').offset();
  var scr_top = $(window).scrollTop();   	
  $(window).scroll(function() {
    if (offset_this.top <= scr_top) {
      $('.fixed-block').addClass("fixed");
    } else{
      $('.fixed-block').removeClass("fixed") 	
    }
  });
  $(window).load(function() {
    if (offset_this.top <= scr_top) {
      $('.fixed-block').addClass("fixed");
    } else{
      $('.fixed-block').removeClass("fixed") 	
    }
  });
};
```

#### 2. Если нужно плавно проскролить к id: 

```js
$('.js-scroll').click(function() {
  var target = $(this).attr('href');
  $('html, body').animate({
   scrollTop: $(target).offset().top
  }, 1000);
  return false;
});
```

#### 3. Если нужно плавно проскролить к верху страницы:

```js
$(".js-top").click(function() {
  $("html, body").animate({ scrollTop: 0 }, "slow");
  return false;
}); 
```

#### 4. Если нужно свернуть/развернуть блок с заменой текста в кнопке:

```js
$(".js-toggle").toggle(function() {
  $(this).parents('.help').find('.block').slideDown();
  $(this).text("Свернуть");
}, function() {
  $(this).parents('.help').find('.block').slideUp();
  $(this).text("Развернуть");
}); 
```

#### 5. Если нужно для ретины скриптом подменять url  в картинке:

```js
if($('.js-img').length) {     
  if(window.devicePixelRatio > 1) {
    var lowresImages = $('img.js-img');
    lowresImages.each(function(i) {
      var lowres = $(this).attr('data-original');
      var highres = lowres.replace(".png", "@2x.png");
      var highresJpg = lowres.replace(".jpg", "@2x.jpg");
      $(this).attr('data-original', highres);
      $(this).attr('data-original', highresJpg);
    });
  }        
} 
```

#### 6. Если нужно по клику увеличивать или уменьшать число счётчике:

```html
<span class="counter">
  <span class="counter__input">
    <input type="text" value="10">
  </span>
  <span class="counter__button">
    <span class="counter__link counter__link_next"></span>   
    <span class="counter__link counter__link_prev"></span> 
  </span>
</span>
```
```js
$('.counter__link_prev').click(function() {
  var $input = $(this).parents('.box-counter').find('input');
  var count = parseInt($input.val()) - 1;
  count = count < 1 ? 1 : count;
  $input.val(count);
  $input.change();
  return false;
});
$('.counter__link_next').click(function() {
  var $input = $(this).parents('.box-counter').find('input');
  var count = parseInt($input.val()) + 1;
  count = count > ($input.attr("maxlength")) ? ($input.attr("maxlength")) : count;
  $input.val(count);
  $input.change();
  return false;
});
```

#### 7. По клику вне блока закрывать его:

```js
$(document).on('touchstart click', function(e) {
  if ($(e.target).parents().filter('.main-nav:visible').length != 1) {
    $('.main-nav').removeClass('open-nav');
  }
});
```

#### 8. Инициализация Яндекс карты:

```js
if ($('#map').length) {
  ymaps.ready(function() {
    var myMap = new ymaps.Map('map', {
    center: [55.760874, 37.718076],
    zoom: 15
  }, {
    searchControlProvider: 'yandex#search'
  }),
    myPlacemark = new ymaps.Placemark(myMap.getCenter(), {
    hintContent: ''
  }, {
    iconLayout: 'default#image'
  });
    myMap.geoObjects.add(myPlacemark);            
    if (/Android|webOS|iPhone|iPad|iPod|BlackBerry/i.test(navigator.userAgent)) {
      myMap.behaviors.disable('multiTouch');
      myMap.behaviors.disable('scrollZoom');
      myMap.behaviors.disable('drag');
    }
  });
};
```

#### 9. Инициализация Гугл карты, стилизованная:

https://gist.github.com/MokusM/0aa4273a1dfc69aa4d004c3fb132a007 

#### 10. Еслим нужно при адаптации вырезать блок и вставить в другое место:

```js
if (viewport_wid <= 767) {
  $('.col-country').detach().insertAfter($('.customers'));
}
if (viewport_wid > 767) {
  $('.col-country').detach().insertAfter($('.customers-map'));
}
```


## Слова, часто используемые в CSS-классах

### Изображения

`image`, `img`, `picture`, `pic` — картинка<br>
`icon` — иконка<br>
`logo` — логотип<br>
`userpic`, `avatar` — юзерпик, маленькая картинка пользователя<br>
`thumbnail`, `thumb` — миниатюра, уменьшенное изображение<br>

### Текст

`title`, `subject`, `heading`, `headline`, `caption` — заголовок<br>
`subtitle` — подзаголовок<br>
`slogan` — слоган<br>
`lead`, `tagline` — лид-абзац в тексте<br>
`text` — текстовый контент<br>
`desc` — описание, вариант текстового контента<br>
`excerpt` — отрывок текста, обычно используется перед ссылкой «Читать далее...»<br>
`link` — ссылка<br>
`copyright`, `copy` — копирайт

### Списки

`list`, `items` — список<br>
`item` — элемент списка<br>

### Блоки

`page` — корневой элемент страницы<br>
`header` — шапка (страницы или элемента)<br>
`footer` — подвал (страницы или элемента)<br>
`section` — раздел контента (один из нескольких)<br>
`body` — основная часть (страницы или элемента)<br>
`content` — содержимое элемента<br>
`sidebar` — боковая колонка (страницы или элемента)<br>
`aside` — блок с дополнительной информацией<br>
`widget` — виджет, например, в боковой колонке<br>

### Раскладка

`wrapper`, `wrap` — обёртка, обычно внешняя<br>
`inner` — внутренняя обёртка<br>
`container`, `holder`, `box` — контейнер<br>
`grid` — раскладка (страницы или элемента) в виде сетки (обычно содержит в себе `row` и `col`)<br>
`row` — контейнер в виде строки<br>
`col`, `column` — контейнер в виде столбца

### Элементы управления

`button`, `btn` —  кнопка, например, для отправки формы<br>
`control` — элемент управления, например, стрелки «Вперёд/назад» в фотогалерее, кнопки управления слайдером<br>
`dropdown` — выпадающий список<br>

### Медиавыражения

`phone`, `mobile` — мобильные устройства<br>
`phablet` — телефоны с большим экраном (6-7")<br>
`tablet` — планшеты<br>
`notebook`, `laptop` — ноутбуки<br>
`desktop` — настольные компьютеры<br>

### Размеры

`tiny` — маленький, крохотный<br>
`small` — небольшой<br>
`medium` — средний<br>
`big`, `large` — большой<br>
`huge` — огромный<br>
`narrow` — узкий<br>
`wide` — широкий<br>

### Разное

`search` — поиск<br>
`socials` — блок иконок соцсетей<br>
`advertisement`, `adv`, `commercial`, `promo` — рекламный блок (режутся Адблоком, не рекомендуется использовать такие классы для блоков с внутренней рекламой)<br>
`features`, `benefits` — список основных особенностей товара, услуги<br>
`slider`, `carousel` — слайдер, интерактивный элемент с прокруткой содержимого<br>
`pagination` — постраничная навигация<br>
`user`, `author` — пользователь, автор записи или комментария<br>
`meta` — блок с дополнительной информацией, например, блок тегов и даты в посте<br>
`cart`, `basket` — корзина<br>
`breadcrumbs` — навигационная цепочка, «хлебные крошки»<br>
`more`, `all` — ссылка на полную информацию<br>
`modal` — модальное (диалоговое) окно<br>
`popup` — всплывающее окно<br>
`tooltip`, `tip` — всплывающее подсказки<br>
`preview` — анонс, отрывок, например новости или поста, может состоять из заголовка, описания и картинки. Предполагается ссылка на полную версию<br>

### Состояния

`active`, `current` — активный элемент, например, текущий пункт меню<br>
`hidden` — скрытый элемент<br>
`error` — статус ошибки<br>
`warning` — статус предупреждения<br>
`success` — статус успешного выполнения задачи<br>
`pending` — состояние ожидания, например, перед сменой статуса на error или success<br>
