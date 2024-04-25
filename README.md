# Responsive Piano

This project is a simple, responsive piano keyboard built with HTML and CSS.

## HTML Structure

The HTML structure of the piano is defined in `piano.html`. The piano itself is a `<div>` with the id `piano`, which contains another `<div>` with the class `keys`. Each key on the piano is represented by a `<div>` with the class `key`. Black keys have an additional class `black--key`.

## CSS Styles

The styles for the piano are defined in `style.css`. The `box-sizing` property is set to `border-box` on the `html` element and inherited by all other elements. This makes the layout calculations easier to manage.

The `#piano` element is styled to represent the body of the piano, and the `.keys` element contains the individual keys.

Each `.key` element is styled to look like a piano key, with white keys being the default. The black keys are styled with an additional class `black--key`.

The `::after` pseudo-element is used with the `.key.black--key` selector to create the visual effect of black keys.

## Responsiveness

The piano is made responsive with two `@media` queries. When the viewport width is 768px or less, the width of the piano and keys is reduced. When the viewport width is between 769px and 1199px, a different width is applied.

This ensures that the piano display is optimized for different screen sizes.