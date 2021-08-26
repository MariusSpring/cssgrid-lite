# cssGrid Lite

A simple grid library for CSS, based on Tailwind's grid utility classes. Supports breakpoints!


## Documentation

https://tailwindcss.com/docs/grid-template-columns

https://tailwindcss.com/docs/grid-column

## Examples

The example below creates a 12-grid layout with two elements that take up half the grid each on tablet and up. It also adds a gap of 2rem on the X-axis, and 4rem on the Y-axis.

```html
<div class="grid grid-cols-12 grid-gap-x-2 grid-gap-y-4">
  <div class="cols-span-12 cols-md-span-6">
    Half of grid 1
  </div>
  <div class="cols-span-12 cols-md-span-6">
    Half of grid 2
  </div>
</div>
```
