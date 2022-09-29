# Card Print CSS

> Stylesheet for printing cards, labels, vignettes

This CSS file is designed to print your own CSS formatted cards, vignettes, labels.
You can add `.page` and `.card` elements to your document to create your print layout.

## Installation

Import the stylesheet to your HTML document.

```html
<link rel="stylesheet" href="path/to/card-print.css">
```

## Usage

Add your cards to pages and print through your browser's print dialog.

```html
<div class="page">
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
</div>
```

You can configure your pages, cards and layout with the following CSS variables:

```css
:root {
  --card-width: 2.5in;
  --card-height: 3.5in;

  --page-width: 8.5in;
  --page-height: 11in;
  --page-margin: 0.25in;

  --col-count: 2;
  --row-count: 2;
}
```

When printing, make sure to set the page size to the same as you specified with the variables, and to set the margins to none.

## Contributing

All ideas, recommendations, bug reports, pull requests are welcome. :smile:
