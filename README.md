jquery-focusable
================

jQuery plugin to enable focus and arrow keys navigation on elements.

Use tab/shift+tab to navigate among lists and arrow keys to navigate among items.

## Usage

Load the script after jQuery.

```html
<script src="js/jquery-2.1.0.js"></script>
<script src="js/focusable.js"></script>
```

Markup is very simple.

```html
<ul>
  <li>Item 1.1</li>
  <li>Item 1.2</li>
  <li>Item 1.3</li>
</ul>
<ul>
  <li>Item 2.1</li>
  <li>Item 2.2</li>
  <li>Item 2.3</li>
</ul>
<ul>
  <li>Item 3.1</li>
  <li>Item 3.2</li>
  <li>Item 3.3</li>
</ul>
```

Start the plugin.

```html
<script>
$("ul").focusable();
</script>
```
