# Stackenblochen grid system

## Description

Stackenblochen is a stylus grid system for rectanglers.

It is inspired by the [foundation](http://foundation.zurb.com/docs/components/grid.html) grid system and works very similar.

## Installation

You can either copy the `stackenblochen.styl` in your project, or install it via [bower](http://bower.io/):

```sh
bower install stackenblochen --save
```

## Usage

Configure and include the `stackenblochen.styl` in your stylus file:

```stylus
// Default values
$grid-columns = 12
$grid-gutter = 2rem
$grid-width = 75rem
$grid-medium = 25em
$grid-large = 50em

@import 'stackenblochen'
```

In your html, do something like this:

```html
<div class="grid">
  <div class="small-12 large-6 columns"></div>
  <div class="small-6 large-3 show-on-medium columns"></div>
  <div class="small-6 large-3 hide-on-medium columns"></div>
  <div class="small-12 columns"></div>
</div>
<div class="grid hide-on-large">
  <div class="small-6 medium-4 small-centered columns">
    <div class="grid">
      <div class="small-6 columns"></div>
      <div class="small-6 columns"></div>
    </div>
</div>
```

It can even be nested!

## Stackenblochen??

[https://www.youtube.com/watch?v=zqAdxN1IWQQ](https://www.youtube.com/watch?v=zqAdxN1IWQQ)
