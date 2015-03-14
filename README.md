# Splinter - Grid System [beta]
*yesss, it's beta. Work in progress.. if something isn't working, pls tell me.*

Splinter is a highly customizable responsive grid system written in scss. Simply adjust the variables to your needs and compile the code to css. It works in all modern browsers and IE9+. 

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

## Settings
### Customize your own grid
With Splinter it's possible to customize a lot of things before you start using the grid system. All you have to do is adjust the variables and compile the code to css. You can change the number of columns, the row and gutter width, set your breakpoints, and change the naming of every part of the class names. If you don't want to use a prefix in your class names, just change the variable to an empty string: "".
```scss
$grid-columns:				12				!default;
$grid-row-width:			1200px			!default;
$grid-gutter-width:			15px 			!default;

$grid-query-width-sm:		35.563em 		!default; // 569px
$grid-query-width-md:		48.063em 		!default; // 769px
$grid-query-width-lg:		64.063em 		!default; // 1025px

$grid-prefix:				g- 				!default;
$grid-row:					row12			!default;
$grid-col:					col 			!default;
$grid-push:					push 			!default;
$grid-pull:					pull 			!default;
$grid-offset:				offset 			!default;
$grid-media-query-xs: 		--xs 			!default;
$grid-media-query-sm: 		--sm 			!default;
$grid-media-query-md: 		--md 			!default;
$grid-media-query-lg: 		--lg 			!default;
```

## Support
### If you have any questions, feel free to contact me
- [@JordyPouw](https://twitter.com/JordyPouw "Just send me a tweet :)")