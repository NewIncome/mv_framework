# mv_framework
This project is to take everything learned so far and use it to build our own simple grid-based framework (the scss file).
It also consists of a second part which is building a website with the recently made framework; site built: [getfedora](https://getfedora.org/).

Technologies used: **HTML**, **CSS** and **SASS**.

## Content:

Main usage points for the framework used with css, main topics:
1. [Breakpoints](#Breakpoints)
2. [Sizes](#Sizes)
3. [Sides](#Sides)
4. [Paddings and Margins](#Paddings-Margins)
5. [Classes](#Classes)
6. [Alignment](#Alignment)
7. [Border](#Border)
8. [Floats](#Floats)
9. [Positions](#Positions)
10. [Utilities](#Utilities)



## Breakpoints:
For added responsiveness for different screen sizes
- xs -> 425px
- sm -> 575px
- md -> 767px
- lg -> 1024px
- xl -> 1440px

## Sizes:
For col Sizes
- columns go inside rows and are divided in 12 spans (1 - 12)
For paddings and margins
- from -8 to 8 which translates to: -4rem to 4rem

## Sides:
Used mainly for paddings, margins
- t -> top
- b -> bottom
- l -> left
- r -> right

## Paddings-Margins:
For each side and for each breakpoint
  - p(side)-(breakpoint)
    - pt, pb, pl and pr (e.g.: pr-xs)
  - m
    - mt, mb, ml and mr

## Classes:
For positioning elements (used mainly for positioning with flex property)
- container
- container-fluid
- col
  - (e.g.: col-xs-1)
  - can work with breakpoints
  - flex-col

## Alignment:
For x-axis justify-content:
- flex-
  - center, start, end , between and around
For y-axis align-self:
- align-
  - center, start and end

## Border:
Used with rem values from 0 to 4 and worked with for 2 corners at a time
- top (top left and right)
- bottom (bottom left and right)
- left (left top and bottom)
- right (right top and bottom)

## Floats
Used for floats and clear:
- float-
  - l (left), r(right), n(none)
- clear-
  - l(left), r(right), n(none), b(both)

## Positions
Used for setting positiong of elements:
- pos-
  - rel(relatve), abs(absolute), fix(fixed)
  
## Utilities
Used to set stling to the text:
Setting text size:
- text-
  - from 1 to 8 which translates to: 0.5rem to 4rem
Setting font weight:
- text-
  - b(bold), n(normal), l(lighter)

## Githack Clone link:
* [Production](https://rawcdn.githack.com/NewIncome/mv_framework/b1cfb3e2ecbe3193fe6d7c0096fb541def15fcd0/index.html)

* [Development](https://raw.githack.com/NewIncome/mv_framework/feature/index.html)



For more info, check the [Odin Project](https://www.theodinproject.com/courses/html5-and-css3/lessons/design-your-own-grid-based-framework)


## Collaborators & profiles link:
- Allison Peres - [GitHub](https://github.com/alissonperes)
- J.Alfredo Cardenas - [GitHub](https://github.com/newincome)
