# learn-web
Learn how to use HTML, CSS and JavaScript together

## HTML
HTML is a markup language that is made up of blocks. A block can be a group of items, or an element.

Basic example:
```html
<html>
  <head>
    <title>Hello World!</title>
  </head>
  <body>
    <p>Hello World!</p>
  </body>
</html>
```

Where `<html>` contains everything, `<head>` contains information for the browser (title, description, styling locations, etc) and `<body>` contains the visual content.

## CSS
CSS is a visual language that dictates the styling of HTML.

Basic example:
```css
p {
  background-color: 'green';
  color: 'red';
}
```

Where `p` is a *selector* for the HTML element `<p>`, and `background-color`, etc are attributes in the form of `key/value` pairs.

## JavaScript
JavaScript is the main programming language for the web, which is parsed by web browsers.

Basic example:

```js
var bucket = 10;

var newBucket = bucket + 10;

console.log(newBucket);
```

Where `var` declares a new `variable` or `data store`, `=` assigns a value, and `10` is a number unit.

