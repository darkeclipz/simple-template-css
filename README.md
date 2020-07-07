# Simple Template

This repository contains a simple template that can be used to start developing a new web application.

Most elements are styled by default, such as: buttons, inputs and tables.

## How to use

First create a `div` element that holds the flex box settings.

 * `flex` : enables flexbox.
 * `flex-column` : flex column direction.
 * `flex-wrap` : enables flex wrapping.
 * `card-container` : holds cards, to align the properly.

Now we need to add a grid element in a `div`, options here are:

 * `grid` : simple 100% width.
 * `grid-2` : duo layout, 50% width.
 * `grid-3` : three elements layout, 33.33% width.
 * `grid-4` : four elements layout, 25% width.

Within the grid we can place a card, here we have `card`, `card-title`, `card-image` which can be set to `full`, and `card-body` for the content.

Now you can simple place your favorite elements, and they will be styled properly. 

If you need some horizontal space, use `<hr />` and if you don't want to see it make it `hidden`.

Tables are also quite easy. Use the `header` class and `thead` to give a header. Borders can be removed with `no-border` which should be used with `full` to remove some margin.

This CSS is terrible to use with any other framework, because it uses the HTML selectors directly. Plus side of this, and why it's worth it, is very small HTML files, because you don't need millions of classes.

## Demo

[See the example page here.](https://darkeclipz.github.io/simple-template-css/)

## Why

This idea grew out of frustration of Bootstrap like frameworks, which gives millions of CSS classes, and yet doesn't give me the layout I want.

## Licence

Do whatever the fuck you want with it.