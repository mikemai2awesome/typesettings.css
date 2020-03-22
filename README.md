# Typesettings.css
Typesettings.css is inspired by traditional graphic design fundamentals and the perfect lightweight CSS framework for any minimal website or article design. No colors; no Javascript; no classes!

## Basic Usage
### 1. Include typesettings.css in the HTML file's `<head>` section:

```html
<head>
  <link rel="stylesheet" href="[path]/typesettings.css">
</head>
```

Note: If you are using typesettings.css as is, don't combine it with other frameworks. Also, basic resets are included, there is no need to use Normalize.css or Sanitize.css.

### 2. Add `data-typesettings` attribute to the direct child element of the `<body>`:

```html
<body>
  <div data-typesettings>
    …
  </div>
</body>
```

## Enhanced elements
All of these HTML elements can be used inside the `div[data-typesettings]` element without any classes. It's that easy!

* p
* dl
* ol
* ul
* nav
* aside
* footer
* header
* section
* h1 ~ h6
* blockquote
* fieldset
* details
* button
* figure
* input
* label
* small
* table
* abbr
* code
* form
* pre
* hr

## Browser Support
This framework is built for all browsers but IE, cuz fuck it.
