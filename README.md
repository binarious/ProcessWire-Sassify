# ProcessWire Sassify #

This module allows you to use SASS/SCSS/Compass with your ProcessWire templates.

# How to use #


### Single SASS/SCSS file ###

```
<link rel="stylesheet" type="text/css" href="<?php echo Sassify::css('sass/my_style.scss'); ?>">
```

### Array of SASS/SCSS files ###

```
<link rel="stylesheet" type="text/css" href="<?php echo Sassify::css([
	'sass/style_1.scss',
	'sass/style_2.scss',
	'sass/style_3.scss',
]); ?>">
```