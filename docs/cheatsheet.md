# Erläuterung der verwendeten Zeichen und Symbole

## Listen

### Unsortierte Listen
-   Rot
-   Grün
-   Blau

### Sortierte Listen
1.  Hund
2.  Katze
3.  Maus

### Umbrüche in Listen
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

### Listenpunkte mit mehreren Absätzen
1.  Dies ist eine Listenpunkt mit zwei Absätzen. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

## Horizontale Linien
***

### Links

Ein Link zu [google](https://google.de) zum Bseipsiel.
Dies ist [ein Beispiel][1] für einen Referenz-Link.

## Betonung

*Einzelne Sternchen*

_Einzelne Unterstriche_

**Doppelte Sternchen**

__Doppelte Unterstriche__


## Tabellen

First Header | Second Header | Third Header
:----------- |:-------------:| -----------:
Left         | Center        | Right
Lorem ipsum dolor sit amet, consectetur adipisicing elit.         | Vero laboriosam quaerat maiores non, natus necessitatibus earum recusandae consectetur        | omnis pariatur architecto esse! Magni quibusdam nisi vero, in voluptas quia a!


## Code Blöcke

### PHP
``` php
<?php
define('MY_CONST', "My Constant");
$foo = new Bar();
if($foo->baz(MY_CONST) !== true) {
    // do something ...
}
?>
```

### JS
```js
(function () {
    const foo = 'bar';
    let baz = function () {
        alert('Hello ' + foo);
    }
    baz();
})();
```

### Zeilennummerierung
``` js linenums="1"
(function () {
    const foo = 'bar';
    let baz = function () {
        alert('Hello ' + foo);
    }
    baz();
})();
```
### Zeilennummerierung und Hervorhebung (44, 46)
```js hl_lines="3 5" linenums="42"
// Eine Datei ab Zeile 42 ...
import foo.bar
import boo.baz
import foo.bar.baz
function init() {
}
```

Code innerhalb von Fließtext ist auch möglich, z.B. `#!js var test = 0;` etc.

## Grafiken

### Grafik als ```figure``` mit ```caption```

!![Caption Text](img/test-001.jpg)

### Grafik als ```figure``` mit ```caption``` und ```title```

!![Caption Text][g1]

### Grafik als ```image``` mit ```title```
![Logo alt text][logo-img-only]


## HTML Attribute

Dieser Absatz hat ```foo``` und ```bar``` als ```class```.
{: class="foo bar" title="Some title!" }

## Hinweise

### Eine Notiz

!!! note "Eine Notiz"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Ein Tipp

!!! tip "Ein Tipp"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Eine Warnung

!!! warning "Eine Warnung"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Ein Gefahrenhinweis

!!! danger "Ein Gefahrenhinweis"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

## Fußnoten

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]

## Aufgabenlisten

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3


## SmartSymbols

- (tm)
- (c)
- (r)
- c/o
- +/-
- -->
- <--
- <-->
- =/=
- 1/4, 2/3, 5/6
- 1st 2nd 3rd


## Marker

==mark me==


## Inhaltsübersicht:

[TOC]





[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


[1]: https://google.de  "google Deutschland"
[g1]: img/test-001.jpg  "Optionales title-Attribut"
[logo-img-only]: img/test-001.jpg "Logo Title"

