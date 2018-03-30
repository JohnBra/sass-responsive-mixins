# sass-responsive-mixins

This is a simple collection of mixins with variable breakpoints for media queries, optimally packed in a sass partial imported into your s.

## Why?

* Readable code-structure
* Consistency over multiple components
* Easily changeable breakpoints
* Easy to add additional break points

## Code and Demo

* Checkout the [Demo](https://www.google.com) here.
* Checkout the [Code](https://www.google.com) here.

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