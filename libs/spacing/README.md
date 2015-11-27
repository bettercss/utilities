<p class="u-text-emphasize">This library provides utilities to help space elements</p>

### .u-margin-[top|left|right|bottom]

Sets margin in the direction specified.

```html
<div class="u-flex">
    <div class="u-margin-right u-border">Spacing</div>  
    <div class="u-border">Spacing</div>  
</div>    
```

### .u-margin-[top|left|right|bottom]-remove

Removes margin in the direction specified.

```html
<div class="u-flex">
    <div class="u-margin-right-remove u-border">Spacing</div>  
    <div class="u-border">Spacing</div>  
</div>  
```

### .u-padding-[top|left|right|bottom]

Sets padding in the direction specified.

```html
<div class="u-flex">
    <div class="u-padding-left u-border">Spacing</div> 
</div>
```

### .u-padding-[top|left|right|bottom]-remove

Removes padding in the direction specified.

```html
<div class="u-flex">
    <div class="u-padding-left-remove u-border">Spacing</div> 
</div>
```

## Responsive Suffixes

All classes provided in this library come with breakpoint suffixes. Once set the utility property will only be applied at the specified viewport size.

`@medium, @large`