<p class="u-text-emphasize">This library provides utilities to control typography presentation.</p>

### .u-font-size-[h1|h2|h3|h4|h5|h6|]

Set a heading style based on the heading size specified. 

```html
<span class="u-font-size-h1">Heading</span>  
```

### .u-truncate

Truncate text when hitting the end of an element.

`Note: Doesn't work on inline elements`

```html
<div class="u-truncate u-column-2">Lets get this text to truncate.</div>  
```

### .u-font-weight-[normal|bold|none]

Set font-weight for element.

```html
<div class="u-font-weight-bold">Bold text</div>  
```

### .u-text-transform-[uppercase|lowercase|capitalize|none]

Set text case for element.

```html
<div class="u-text-transform-uppercase">Uppercase</div>  
```

### .u-text-decoration-[underline|line-through|none]

Set text decoration for element.

```html
<div class="u-text-decoration-underline">Underlined Text</div>  
```

### .u-text-align-[center|left|right|justify]

Set horizontal alignment for element.

```html
<div class="u-text-align-center">Centered Text</div>  
```

### .u-vertical-align-[middle|top|bottom]

Set vertical alignment for element.

```html
<div class="u-vertical-align-middle">Vertical Middle</div>  
```

### .u-font-size-[tiny|small|large|huge]

Set font-size based on the size specified.

```html
<div class="u-font-size-tiny">tiny Text</div>  
<div class="u-font-size-small">Small Text</div>  
<div class="u-font-size-large">Large Text</div>  
<div class="u-font-size-huge">Huge Text</div>  
```


## Responsive Suffixes

All classes provided in this library come with breakpoint suffixes. Once set the utility property will only be applied at the specified viewport size.

`@medium, @large`