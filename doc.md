## Principles of writing css

- responsive design(correct units, fluide layouts, media queries, responsive images, desktop-first vs mobile-first)

- maintainable codes(naming classes,reusable, growth,clean)

- web performance(less images, compress images,less code, less http requests, compress code, use css preprocessor(Sass))

# Specificity, order, important

## Units working

- ems: use parent as a reference.For fonts the reference is parent while for length the reference is the current element

- rems: use root as a reference For fonts and lenghts

** vh and vw **

- vh(1% of viewport height)
- vw(1% of viewport width)

## Blocks

- Block-level: box-model applies as showed
- Inline-block: no line-breaks, box-model applies as showed

* inline: no heights and widths

## Positioning schemes

- Normal flow: not floated, not absolutely positioned
- Floats: elements removed from the normal flow
- Absolute positioning : elements are removed from the normal flow, no impact to the surrounding elements, top,bottom, left and right are used to offset the element from its relatively positioned container

### Atomic design
### BEM: Block-Element-Modifier


## Responsive design principles
 1. Fluid grids and layouts(% rather than px)
 2. Flexible and responsive images(images adapting to the current viewport. % are used)
 3. media queries(change styles based on the viewport)

### COMMON BREAKPOINTS
 0 - 600px:        Phone
600 - 900px:        Tablet portrait
900 - 1200px:        Tablet landscape
[1200- 1800] : normal styles are applied here
1800px +:         Big desktop
