---
description: Свойство border-image-outset описывает, насколько область граничного изображения выходит за пределы элемента
---

# border-image-outset

Свойство **`border-image-outset`** задает расстояние, на которое изображение рамки элемента отстоит от его границы.

Части граничного изображения, отображаемые за пределами рамки элемента с параметром `border-image-outset`, не вызывают переполнение полос прокрутки и не захватывают события мыши.

## Демо

<iframe class="interactive is-default-height" height="200" src="https://interactive-examples.mdn.mozilla.net/pages/css/border-image-outset.html" title="MDN Web Docs Interactive Example" loading="lazy" data-readystate="complete"></iframe>

??? info "Фон"

    <div class="col3" markdown="1">

    - [border](border.md)
    - [border-bottom](border-bottom.md)
    - [border-bottom-color](border-bottom-color.md)
    - [border-bottom-left-radius](border-bottom-left-radius.md)
    - [border-bottom-right-radius](border-bottom-right-radius.md)
    - [border-bottom-style](border-bottom-style.md)
    - [border-bottom-width](border-bottom-width.md)
    - [border-collapse](border-collapse.md)
    - [border-color](border-color.md)
    - [border-image](border-image.md)
    - **border-image-outset**
    - [border-image-repeat](border-image-repeat.md)
    - [border-image-slice](border-image-slice.md)
    - [border-image-source](border-image-source.md)
    - [border-image-width](border-image-width.md)
    - [border-left](border-left.md)
    - [border-left-color](border-left-color.md)
    - [border-left-style](border-left-style.md)
    - [border-left-width](border-left-width.md)
    - [border-radius](border-radius.md)
    - [border-right](border-right.md)
    - [border-right-color](border-right-color.md)
    - [border-right-style](border-right-style.md)
    - [border-right-width](border-right-width.md)
    - [border-style](border-style.md)
    - [border-top](border-top.md)
    - [border-top-color](border-top-color.md)
    - [border-top-left-radius](border-top-left-radius.md)
    - [border-top-right-radius](border-top-right-radius.md)
    - [border-top-style](border-top-style.md)
    - [border-top-width](border-top-width.md)
    - [border-width](border-width.md)
    - [box-shadow](box-shadow.md)

    </div>

## Синтаксис

```css
/* <length> value */
border-image-outset: 1rem;

/* <number> value */
border-image-outset: 1.5;

/* top and bottom | left and right */
border-image-outset: 1 1.2;

/* top | left and right | bottom */
border-image-outset: 30px 2 45px;

/* top | right | bottom | left */
border-image-outset: 7px 12px 14px 5px;

/* Global values */
border-image-outset: inherit;
border-image-outset: initial;
border-image-outset: revert;
border-image-outset: revert-layer;
border-image-outset: unset;
```

## Значения

Значение по-умолчанию:

```css
border-image-outset: 0;
```

## Спецификации

- [CSS Backgrounds and Borders Module Level 3](https://w3c.github.io/csswg-drafts/css-backgrounds/#the-border-image-outset)

## Поддержка браузерами

<p class="ciu_embed" data-feature="border-image" data-periods="future_1,current,past_1,past_2">
  <a href="http://caniuse.com/#feat=border-image">Can I Use border-image?</a> Data on support for the border-image feature across the major browsers from caniuse.com.
</p>
