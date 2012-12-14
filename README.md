hidpi.scss
==========

A HiDPI SCSS mixin based on retina.js' implementation.

Defaults to png but can be overwritten to jpg or gif
$image name is equal to the image name with out it's extention - 'example.png' would be defined as 'example'

Example:
--------
    @include at2x('../img/icon', 22px, 21px, '.png');
