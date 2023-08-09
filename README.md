# Preload with Responsive Design

The following example shows how to use the `preload` option when using responsive design. This
will load more than one style depends on the width of the screen. In this example, there are two style files, one for the larage screens and the other on for the small screens (mobiles & tablets).

```html
    <link
        rel="preload"
        href="assets/css/style.css"
        as="style"
        media="(min-width: 601px)"
    >
    <!--... -->
    <link
        rel="preload"
        href="assets/css/style.sm.css"
        as="style"
        media="(max-width: 600px)"
    >
```