# flatsheet-base-css

Base css styles for [flatsheet](http://github.com/flatsheet) projects.

## Warning

Hey, this is really just for flatsheet stuff. You most likely won't benefit from it at all. But if you appreciate the approach, feel free to fork or copypasta this code around.

## How we use this

This module is used along with the [flatsheet-base-html](http://github.com/flatsheet/flatsheet-base-html) module to create the most basic of page layout and default styles.

## Install

```
npm i --save flatsheet-base-css
```

## Usage

Import into style.css file:

```css
@import "flatsheet-base-css";
```

then:

```
sheetify style.css > bundle.css
```

Or import source file into your style.css file:

```css
@import "flatsheet-base-css/source.css";
```

then:

```
sheetify style.css | myth > bundle.css
```

## License

[MIT](LICENSE.md)
