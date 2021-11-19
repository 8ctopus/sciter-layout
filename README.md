# sciter layout demo app

This is a [sciter.js](https://sciter.com/) demo app that explores different layout possibilities in sciter.

![sciter layout screenshot](screenshot.png)

## demo

- git clone the repository
- on Linux/Mac `chmod +x install.sh start.sh`
- run `install.bat` (Win) or `./install.sh` (Linux/Mac) to download the latest sciter binaries and the sciter package manager
- run `start.bat` (Win) or `./start.sh` (Linux/Mac)

# layout

sciter layout concepts are introduced in this article

[https://terrainformatica.com/w3/flex-layout/flex-vs-flexbox.htm](https://terrainformatica.com/w3/flex-layout/flex-vs-flexbox.htm)

## flow

`flow` is the sciter analog to `display:flex`. Possible values are:

- `horizontal` contained elements are on a horizontal line
- `vertical` contained elements are on a vertical line
- `horizontal-wrap` same as above with wrapping to the next line when the line is too long
- `row(item1, item2, ...)` items are on a horizontal line
- `grid` custom layout
- `stack` elements are on top of each other
- `table`, `table-fixed` ? add an example

## flex length units

Flex length units are "weights" used in distribution of free space along some direction.

[https://sciter.com/css-extensions-in-h-smile-engine-part-ii-flex-units/](https://sciter.com/css-extensions-in-h-smile-engine-part-ii-flex-units/)

### %%

```css
width: 50%;
margin-left: 30%%;
margin-right: 70%%;
```

### *

1* == 100%%

```css
width: 50%;
margin-left: 1*;
margin-right: 2*;
```
