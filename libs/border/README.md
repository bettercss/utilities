<p class="u-text-emphasize">This library provides utilities to add borders types to elements.</p>

## .u-border-color

Sets the border to `solid 1px #ccc`.

```html
<div class="u-border u-padding-small">Border</div>  
```

### .u-border-[top|left|right|bottom]

Sets border color to `solid 1px #ccc` for the direction specified.

```html
<div class="u-border-color-left u-padding-small">Border Left</div> 
```

### .u-border-none

Removes borders.

```html
<div class="u-border-none">No Borders</div>
```

### .u-border-rounded

Sets border-radius to `10px` giving the element rounded corners.

```html
<div class="u-border-rounded u-border u-padding-small">Rounded</div>
```

### .u-border-rounded-[top|right|left|bottom]

Sets border-radius to `10px` giving the element rounded corners for the direction specified.

```html
<div class="u-border-rounded-top u-border u-padding-small">Rounded Top</div>
```

### .u-border-circle

Sets border-radius so element is appears round.

```html
<span class="u-border-circle u-border u-padding-small">10</span>
```

## Responsive Suffixes

All classes provided in this library come with breakpoint suffixes. Once set the utility property will only be applied at the specified viewport size.

`@medium, @large`