# Splinter - Scss Grid System

Splinter is a highly customizable responsive grid system written in scss. Simply adjust the variables in the settings sections and compile the code to css. It works in all modern browsers and IE9+.

## Quick start

### Link the stylesheet to your document
```html
<link rel="stylesheet" href="css/splinter.min.css">
```

### Structure your layout
```html
<div class="g-row12">
  <div class="g-col12--xs g-col6--md">
    Content
  </div>

  <div class="g-col12--xs g-col6--md">
    Content
  </div>
</div> 
```

## Documentation
### Customize your own grid
With Splinter it's possible to customize a lot of things before you start using the grid system. All you have to do is adjust the variables and compile the code to css. You can: 
- Change the number of columns.
- Change the row and gutter width
- Set your breakpoints
- Filter out the push, pull or offset methods.
- Change the naming of every part of the class names. 

*Note: If you don't want to use a prefix in your class names, you can just change the variable to an empty string: "".*

```scss
// $ Settings.
// ==================================================
$grid-columns:          12        !default;
$grid-row-width:        1200px    !default;
$grid-gutter-width:     30px      !default;
$grid-query-width-sm:   568px     !default;
$grid-query-width-md:   768px     !default;
$grid-query-width-lg:   1024px    !default;

$grid-create-push:      true      !default;
$grid-create-pull:      true      !default;
$grid-create-offset:    true      !default;

$grid-prefix:           g-        !default;
$grid-row:              row12     !default;
$grid-col:              col       !default;
$grid-push:             push      !default;
$grid-pull:             pull      !default;
$grid-offset:           offset    !default;
$grid-suffix-xs:        --xs      !default;
$grid-suffix-sm:        --sm      !default;
$grid-suffix-md:        --md      !default;
$grid-suffix-lg:        --lg      !default;
```

## Support
### If you have any questions, feel free to contact me
- [@JordyPouw](https://twitter.com/JordyPouw "Just send me a tweet :)")