# COME ON MY SELECTOR!

## Description
Replaces all `<select>` tag with a custom SELECTOR that supports css background styling. Replaced selectors are `<div>`s filled with an ul>li stucture. The original select is kept but hidden, its value is updated automatically allowing scripting to be done properly.

This is mainly thought as a workaround for the lack of styling options in Webkit-driven browser (hi Google Chrome :^) ).

## COMS()
Simply call the COMS() function whenever your DOM is ready.
```javascript
// Replace all <select> tags within the document
COMS();
```

* You can disable the console rendering time log by setting the variable `_COMS_exec` to false.
* You can also choose to display the original select by setting the variable `_COMS_hideOriginalSelect` to false
* You can override the default COMS styling by editing the css file. You can also change the default selector class name if needed.

## Usage
[MIT licensed](https://opensource.org/licenses/MIT)
