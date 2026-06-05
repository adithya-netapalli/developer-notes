# Global Attributes

## What are Attributes?

Attributes provide additional information about HTML elements.

Attributes are written inside the opening tag of an element.

Example:

```html
<img src="image.jpg" alt="Image">
```

## Global Attributes

Global attributes are attributes that can be used with all HTML elements.

## Common Global Attributes

### style

Used to apply inline CSS.

```html
<p style="color: red;">Hello World</p>
```

### hidden

Used to hide an element.

```html
<p hidden>Hello World</p>
```

### title

Displays a tooltip when the user hovers over an element.

```html
<p title="Frontend Developer">Adi</p>
```

### class

Used to apply CSS styles to elements.

```html
<p class="heading">Hello World</p>
```

### id

Used to uniquely identify an element.

```html
<p id="title">Hello World</p>
```

### data-*

Used to store custom data for JavaScript.

```html
<button data-id="101">Click Me</button>
```

## Element-Specific Attributes

Some attributes only work with specific elements.

Example:

```html
<img src="image.jpg">
```

The `src` attribute is mainly used with image elements.

## Custom Attributes

We can create our own attributes.

Example:

```html
<p company="hakss">Hello World</p>
```

Custom attributes can be accessed using JavaScript.

## Summary

- Attributes provide additional information about elements.
- Global attributes can be used with all HTML elements.
- Common global attributes are `style`, `hidden`, `title`, `class`, `id`, and `data-*`.
- Some attributes are specific to certain elements.
- Developers can create custom attributes when needed.
