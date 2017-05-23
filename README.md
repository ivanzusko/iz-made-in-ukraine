# iz-made-in-ukraine

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ivanzusko/iz-made-in-ukraine)

My very first custom element which just displays svg barcode with **Made in Ukraine** sign

<!--
```
<custom-element-demo>
  <template>
    <script src="iz-made-in-ukraine.js"></script>
    <iz-made-in-ukraine></iz-made-in-ukraine>
  </template>
</custom-element-demo>
```
-->


## Usage
You can pass any valid css property via `data-` if is needed:
```html
<iz-made-in-ukraine 
    data-max-width="200px"
    data-background-color="#f4f4f4"></iz-made-in-ukraine>
```
By default it will be `100px` minimal width, but will take the full width of the parent


## License
MIT
