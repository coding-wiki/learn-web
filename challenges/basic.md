# Basic Challenges

Use a website that lets you write HTML, CSS and JavaScript in the same window such as [JSFiddle](https://jsfiddle.net/).

1. Create a basic page with the text `Hello world!`.
  - You will need to use the elements `<html>`, `<head>`, `<body>` and `<p>`
  - This is the basic template of any page:
  ```html
  <html>
    <head>
      <title>Hello World!</title>
    </head>
    <body>

    </body>
  </html>
  ```
  - How do you add text?
    - You can directly write `Hello world!` inside of <body>, but it is best practise to put it inside a dedicated element such as `<p>` for paragraphs.
  - `<p>Hello World!</p>` would go inside of `<body>`  
    

2. Give the page some styling: Change the `background-color` to green and text `color` to blue
  - You will need to use `CSS selectors` as such: 
  ```css
  p {
    color: white;
  }
  body {
    background-color: (what goes here?);
  }
  ```
  
3. Set the text of `<p>Hello World!</p>` to `Hi!`:

```html
<body>
  <p id="helloText"></p>
</body>
```

``js
var helloText = document.getElementById('helloText');

helloText.innerHTML = 'Hi!';
```
