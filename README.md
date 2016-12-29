# sorttable
Ripoff and update of the sorttable from http://www.kryogenix.org/code/browser/sorttable/ by Stuart Langridge

This is a cleaner one without polyfill and updates for DOM manipulations

This code is interesting as plain vanilla and nearly clean. It needs more a little modernization yet.

## Licence

I correct and publish it in the same original MIT licence, as in http://www.kryogenix.org/code/browser/licence.html

## How to use it

Insert the lib loader at you convenience. Classic HTML would put it like that in the `<head>` tag :

```html
<script src="./libs/sorttable.js"></script>
```

To have a `<table>` sortable :

1. add a `sortable` class to it
2. You must have a `<thead>` and a `<tbody>` sections
3. in JS, call `sorttable.init()` or more specifically `sorttable.makeSortable(table_element)`
