# sass-responsive-mixins

This is a simple collection of mixins with variable breakpoints for media queries, optimally packed in a sass partial imported into your stylesheets.

## Why?

* Readable code-structure
* Consistency over multiple components
* Easily changeable breakpoints
* Easy to add additional break points

## Code and Demo

* Checkout the [Demo](https://johnbra.github.io/sass-responsive-mixins/) here.
* Checkout the [Code](https://github.com/JohnBra/sass-responsive-mixins/blob/master/src/styles/_responsive.scss) here.

## Usage

* add optional styles folder into your src directory
* add ``_responsive.scss`` to your style or src directory
* import the ``mixins`` into your component stylesheet like so:
```scss
@import '../styles/responsive';
```
* include the ``mixins`` in your elements like so:
```scss
.some-element{
    @include display-res(xs) { font-size: 2.7em }
    @include display-res(sm) { font-size: 3em; }
    @include display-res(md) { font-size: 3.5em; }
    @include display-res(lg xl) { font-size: 5em; }
}
```

## Contributors

* [Bronathan Janaart](https://github.com/JohnBra/) Jonathan Braat - creator, maintainer