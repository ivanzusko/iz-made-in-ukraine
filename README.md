# iz-made-in-ukraine

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ivanzusko/iz-made-in-ukraine)

My very first custom element which just displays svg barcode with **Made in Ukraine** sign

<img width="227" alt="image" src="https://github.com/user-attachments/assets/f0790eb3-2c36-4508-95f3-f220231cafd4">

<!---
```
<custom-element-demo>
  <template>
    <script src="iz-made-in-ukraine.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<iz-made-in-ukraine data-width="200px"></iz-made-in-ukraine>
```


## Usage
You can pass any valid css property via `data-` if is needed:
```html
<iz-made-in-ukraine 
  data-width="200px"
  data-background-color="#f4f4f4"
></iz-made-in-ukraine>
```
By default it will be `100px` minimal width, but will take the full width of the parent


## License
MIT
