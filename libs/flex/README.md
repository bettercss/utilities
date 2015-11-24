# Flex

The `Flex` library is a collection of utlities to handle complex layouts using flexbox layout mode to arrange elements on a page.

## Base

##### .o-flex

Sets the flex display property.

```html
<div class="u-flex">
	<div>column</div>
    <div>column</div>
</div>
```

## Parent Modifiers

##### .u-flex--wrap

Wrap items onto new line when they exceed the viewport.

```html
<div class="u-flex u-flex--wrap">
	<div>column</div>
    <div>column</div>
</div>
```

##### .u-flex--column

Arrange items vertically.

```html
<div class="u-flex u-flex--wrap">
	<div>column</div>
    <div>column</div>
</div>
```

### Alignment

##### .u-flex--center

Vertically center child elements.

```html
<div class="u-flex u-flex--center">
	<div>column</div>
    <div>column</div>
</div>
```

##### .u-flex--stretch

Stretch all elements to fill the height of the parent.

```html
<div class="u-flex u-flex--stretch">
	<div>column</div>
    <div>column</div>
</div>
```

##### .u-flex--baseline

Align child elements to their baseline.

```html
<div class="u-flex u-flex--baseline">
	<div>column</div>
    <div>column</div>
</div>
```

##### .u-flex--start

Align child elements to the top.

```html
<div class="u-flex u-flex--start">
	<div>column</div>
    <div>column</div>
</div>
```

##### .u-flex--end

Align child elements to the bottom.

```html
<div class="u-flex u-flex--end">
	<div>column</div>
    <div>column</div>
</div>
```

##### .o-flex--justify

Automatically fill the space between child elements.

```html
<div class="u-flex u-flex--end">
	<div>column</div>
    <div>column</div>
</div>
```


## Child Modifiers

##### .u-flex--auto

Make an element grow or shrink as needed.

```html
<div class="u-flex">
	<div class="u-flex--auto">column</div>
    <div>column</div>
</div>
```

##### .u-flex--grow

Make an element grow, but not shrink.

```html
<div class="u-flex">
	<div class="u-flex--grow">column</div>
    <div>column</div>
</div>
```

##### .u-flex--none

Prevent an element from growing or shrinking.

```html
<div class="u-flex">
	<div class="u-flex--none">column</div>
    <div>column</div>
</div>
```

##### .u-flex--first

Change the order of child element to first.

```html
<div class="u-flex">
	<div>column</div>
    <div class="u-flex--first">column</div>
</div>
```

##### .u-flex--last

Change the order of child element to last.

```html
<div class="u-flex">
	<div class="u-flex--last">column</div>
    <div>column</div>
</div>
```

## Responsive

Includes responsive classes `[medium, large]`