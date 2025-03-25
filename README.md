# JSAM-RESPONSIVE Documentation

JSAM-RESPONSIVE is a lightweight and flexible CSS framework designed for responsive web layouts. It provides an intuitive grid system and utility classes to make building responsive designs easier, similar to Bootstrap but focused solely on responsiveness.

## Installation

### Using CDN
You can include JSAM-RESPONSIVE in your project by linking the CSS file via CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/jsam-responsive/style.css">
```

### Via npm
You can install JSAM-RESPONSIVE using npm:

```sh
npm install jsam-responsive
```

Then import it in your main CSS or JavaScript file:

```css
@import 'jsam-responsive/style.css';
```

## Grid System (Flexbox-Based)

JSAM-RESPONSIVE provides a simple, flexible, and mobile-first grid system based on `flexbox`. Below are the key classes for structuring layouts:

### Row & Column

To structure content into rows and columns, use the `.row` and `.col-*` classes:

```html
<div class="row">
    <div class="col-6">50%</div>
    <div class="col-6">50%</div>
</div>
```

### Column Sizes

JSAM-RESPONSIVE supports a 12-column grid system, allowing you to create custom layouts:

```html
<div class="row">
    <div class="col-4">33.33%</div>
    <div class="col-8">66.66%</div>
</div>
```

### Responsive Column Classes

To make columns responsive, use breakpoint-specific classes:

```html
<div class="row">
    <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">Responsive Column</div>
</div>
```

## Visibility Utilities

JSAM-RESPONSIVE includes utility classes for hiding elements at different breakpoints:

```html
<p class="d-xs-none">Hidden on extra small screens</p>
<p class="d-sm-none">Hidden on small screens</p>
<p class="d-md-none">Hidden on medium screens</p>
<p class="d-lg-none">Hidden on large screens</p>
```

## Flexbox Utilities

JSAM-RESPONSIVE provides additional flexbox utilities to manage layout structures:

### Direction Control

- `.col` - Vertical flex container
- `.col-reverse` - Reverse column order
- `.row` - Horizontal flex container
- `.row-reverse` - Reverse row order

### Justify Content

- `.justify-start` - Align items to the start
- `.justify-center` - Align items to the center
- `.justify-end` - Align items to the end
- `.justify-between` - Distribute items evenly with space between
- `.justify-around` - Distribute items evenly with space around

### Align Items

- `.align-start` - Align items at the start
- `.align-center` - Align items at the center
- `.align-end` - Align items at the end

## Breakpoints

JSAM-RESPONSIVE follows a mobile-first approach with predefined breakpoints:

| Breakpoint | Size (px) |
|------------|-----------|
| `xs` | `< 576px` |
| `sm` | `≥ 576px` |
| `md` | `≥ 768px` |
| `lg` | `≥ 992px` |
| `xl` | `≥ 1200px` |

## Additional Utility Classes

JSAM-RESPONSIVE includes various utility classes to enhance flexibility:

### Margin & Padding

- `.m-0` to `.m-5` - Margin from 0px to 32px
- `.p-0` to `.p-5` - Padding from 0px to 32px

Example:
```html
<div class="p-3 m-2">Box with padding and margin</div>
```

### Width & Height

- `.w-25` - 25% width
- `.w-50` - 50% width
- `.w-75` - 75% width
- `.w-100` - 100% width
- `.h-100` - 100% height

Example:
```html
<div class="w-50 h-100">Half-width, full height</div>
```

## Example Usage

Below is a complete example of using JSAM-RESPONSIVE to create a simple responsive layout:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JSAM-RESPONSIVE Example</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/jsam-responsive/style.css">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-sm-4">Column 1</div>
            <div class="col-sm-4">Column 2</div>
            <div class="col-sm-4">Column 3</div>
        </div>
    </div>
</body>
</html>
```

## License

JSAM-RESPONSIVE is open-source and available under the MIT License.

## Contribution

We welcome contributions! Feel free to submit issues or pull requests on [GitHub](https://github.com/JSAM-RESPONSIVE).

