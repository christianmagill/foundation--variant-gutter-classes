# foundation--variant-gutter-classes
This project creates additional gutter sizes for Foundation 6, based on multipliers and the responsive gutter settings.

```css
$grid-column-variant-gutter: (
        'half' : .5,
        'double' : 2
);
@include generate-variant-gutter-classes();
```

```html
<div class="row gutter-half">
  <div class="column small-6">Content</div>
  <div class="column small-6">Content</div>
</div>
```
