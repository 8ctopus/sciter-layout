# sciter layout demo app

This is a [sciter.js](https://sciter.com/) demo app that explores different layout possibilities in sciter.

## get started

- git clone the repository
- run `install.bat` to download the latest sciter binaries and library
- start `scapp.exe`
- to refresh the app after changes to the html/css click `F5`

## debug app

- start `inspector.exe`
- inside the `scapp.exe` window click `CTRL + SHIFT + I` to connect to the inspector
- click `CTRL + SHIFT + left click` to inspect an element

## layout

sciter layout concepts are introduced in this article

[https://terrainformatica.com/w3/flex-layout/flex-vs-flexbox.htm](https://terrainformatica.com/w3/flex-layout/flex-vs-flexbox.htm)

flow property possible values

- `horizontal` contained elements are on a horizontal line
- `vertical` contained elements are on a vertical line
- `horizontal-wrap` same as above with wrapping to the next line when the line is too long
- `row(item1, item2, ...)` items are on a horizontal line
- `grid` custom layout
- `stack` elements are on top of each other
- `table`, `table-fixed` ? add an example

# flex length units

Flex length units are "weights" used in distribution of free space along some direction.

[https://sciter.com/css-extensions-in-h-smile-engine-part-ii-flex-units/](https://sciter.com/css-extensions-in-h-smile-engine-part-ii-flex-units/)

## %%

```css
width: 50%;
margin-left: 30%%;
margin-right: 70%%;
```

## *

1* == 100%%

```css
width: 50%;
margin-left: 1*;
margin-right: 2*;
```
