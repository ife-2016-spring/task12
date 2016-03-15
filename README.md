# task12

笔记：

## task12-1

    :nth-child(an+b|odd|even)

Nothing serious.

The values a and b must both be integers, and the index of an element's first child is 1. In other words, this class matches all children whose index fall in the set { an + b; n = 0, 1, 2, ... }.

## task12-2

    transition

Initial value 	as each of the properties of the shorthand:

    transition-delay: 0s
    transition-duration: 0s
    transition-property: all
    transition-timing-function: ease

Applies to 	all elements, ::before and ::after pseudo-elements
Inherited 	no
Media 	interactive
Computed value 	as each of the properties of the shorthand:

    transition-delay: as specified
    transition-duration: as specified
    transition-property: as specified
    transition-timing-function: as specified

Animatable 	no
Canonical order 	order of appearance in the formal grammar of the values

## task12-3

    [element]:checked { style properties }

only checkbox,option and radio

for label can be used to select radios, utlizing the `~` and `+` selector
one can achieve the same thing.

Refer to [css3实现网页平滑过渡效果](http://www.imooc.com/learn/252) on imooc.

however, `:target` is useful as well. I find something really interesting that
in firefox, the default behavior will lead the anchor point into the right place, however,
with no animation.

Refer to [CSS: pure CSS scroll animation](http://stackoverflow.com/questions/17631417/css-pure-css-scroll-animation)

~~Yet another interesting thing, I find `:checked` can not be used after a class selector or id selector rather than element selector
But you can use `:target` in that way.~~

