# Fluent UI Bootstrap 5

Integrate [Bootstrap](https://getbootstrap.com)'s source Sass and compiled JavaScript bundle via npm, with additional features for modern development. This setup includes:

- [Autoprefixer](https://github.com/postcss/autoprefixer) for cross-browser CSS support
- [Stylelint](https://stylelint.io) for maintaining Sass code quality
- [Popper](https://popper.js.org), a Bootstrap JS peer dependency, used for positioning dropdowns, popovers, and tooltips

This project is inspired by [FluentBootstrap](https://github.com/scottkuhl/FluentBootstrap).

### Avoiding Global Styles

To prevent conflicts when embedded in other web applications, the `style.css` file has been configured to avoid modifying global element selectors (such as `body` or `a`). Instead, styles are applied only within containers that have the `fluentbootstrap5body` class. For example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  ...
  <link rel="stylesheet" href="css/styles.css">
</head>

<body class="fluentbootstrap5body">
  ...
</body>
</html>


## How to use

```sh
npm install
npm start
```

View preview page at http://localhost:3000
