# AM SUIT CSS utilities: size


AM SUIT CSS sizing utilities.

Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

## Installation

* [npm](http://npmjs.org/): `npm install am-utils-size`
* [Bower](http://bower.io/): `bower install am-utils-size`

## Available classes

* `[data-am-size~="fit"]` - Make an element shrink wrap its content by floating left.
* `[data-am--size~="fitAlt"]` - Make an element shrink wrap its content by floating right.
* `[data-am-size~="fill"]` - Make an element fill the remaining space.
* `[data-am-size~="fillAlt"]` - An alternative method to make an element fill the remaining space.
* `[data-am-size~="full"]` - Make an element the width of its parent.
* `[data-am-size~="XofY"]` (numerous) - Specify the proportional width of an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

## TODO

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `u-sm-sizeXofY` - To use at the smallest Media Query breakpoint.
* `u-md-sizeXofY` - To use at the medium Media Query breakpoint.
* `u-lg-sizeXofY` - To use at the largest Media Query breakpoint.

### Configuration

There are 3 Media Query breakpoints:

* `--sm-viewport`
* `--md-viewport`
* `--lg-viewport`

When using the [SUIT CSS preprocessor](https://github.com/suitcss/preprocessor),
breakpoints can be configured using `@custom-media`. For example:

## Usage

Please refer to the README for [SUIT CSS utils](https://github.com/suitcss/utils/)

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+

