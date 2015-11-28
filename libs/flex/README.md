<p class="u-text-emphasize">This library provides a collection of utilities to handle complex layouts.</p>

<p>The library uses flexbox layout mode to achieve this, hence the name of the library.</p>

### .u-flex

Sets the flex display property.

```html
<div class="u-flex">
	<div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```

### .u-flex-wrap

Wrap items onto new line when they exceed the viewport.

```html
<div class="u-flex u-flex-wrap">
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```

### .u-flex-column

Arrange items vertically.

```html
<div class="u-flex u-flex-column">
	<div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```

### Alignment

### .u-flex-vertical-center

Set child elements vertically centered.

```html
<div class="u-flex u-flex-vertical-center">
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small u-margin-top-huge u-margin-bottom-huge">column</div>
</div>
```

### .u-flex-horizontal-center

Set child elements horizontal centered.

```html
<div class="u-flex u-flex-horizontal-center">
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small u-margin-top-huge u-margin-bottom-huge">column</div>
</div>
```


### .u-flex-stretch

Stretch all elements to fill the height of the parent.

```html
<div class="u-flex u-flex-stretch">
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-huge">column</div>
</div>
```

### .u-flex-baseline

Align child elements to their baseline.

```html
<div class="u-flex u-flex-baseline u-border-bottom">
   <div><h2 class="u-margin-bottom-remove">Column</h2></div>
    <div><p class="u-margin-bottom-remove">Column</p></div>
</div>
```

### .u-flex-start

Align child elements to the top.

```html
<div class="u-flex u-flex-start u-border-top">
   <div><h2 class="u-margin-bottom-remove">Column</h2></div>
    <div><p class="u-margin-bottom-remove">Column</p></div>
</div>
```

### .u-flex-end

Align child elements to the bottom.

```html
<div class="u-flex u-flex-end u-border-bottom">
   <div><h2 class="u-margin-bottom-remove">Column</h2></div>
    <div><p class="u-margin-bottom-remove">Column</p></div>
</div>
```

### .o-flex-justify

Automatically fill the space between child elements.

```html
<div class="u-flex u-flex-justify">
	<div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```


## Child Items

To control the child items use these utilities.

### .u-flex-auto

Make an element grow or shrink as needed.

```html
<div class="u-flex">
    <div class="u-border u-padding-small u-flex-auto">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```

### .u-flex-grow

Make an element grow, but not shrink.

```html
<div class="u-flex">
    <div class="u-border u-padding-small u-flex-grow">column</div>
    <div class="u-border u-padding-small">column</div>
</div>
```

### .u-flex-none

Prevent an element from growing or shrinking.

```html
<div class="u-flex">
    <div class="u-border u-padding-small u-flex-none">column</div>
    <div class="u-border u-padding-small u-flex-auto">column</div>
</div>
```

### .u-flex-first

Change the order of child element to first.

```html
<div class="u-flex">
    <div class="u-border u-padding-small">First Column</div>
    <div class="u-border u-padding-small u-flex-first">Last Column</div>
</div>
```

### .u-flex-last

Change the order of child element to last.

```html
<div class="u-flex">
   <div class="u-border u-padding-small u-flex-last">First Column</div>
   <div class="u-border u-padding-small">Last Column</div>
</div>
```

## Responsive Suffixes

All classes provided in this library come with breakpoint suffixes `@medium`, `@large`.