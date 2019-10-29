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



## Breakpoints:
for added responsiveness for different screen sizes
- xs -> 425px
- sm -> 575px
- md -> 767px
- lg -> 1024px
- xl -> 1440px

## Sizes:
for col Sizes
- columns go inside rows and are divided in 12 spans (1 - 12)
for paddings and margins
- -8 to 8 which translates to: -4rem to 4rem

## Sides:
used mainly for paddings, margins
- t -> top
- b -> bottom
- l -> left
- r -> right

## Paddings-Margins:
for each side and for each breakpoint
  - p(side)-(breakpoint)
    - pt, pb, pl and pr (e.g.: pr-xs)
  - m
    - mt, mb, ml and mr

## Classes:
for positioning elements (used mainly for positioning with flex property)
- container
- container-fluid
- col
  - (e.g.: col-xs-1)
  - can work with breakpoints
  - flex-col

## Alignment:
for x-axis justify-content:
- flex-
  - center, start, end , between and around
for y-axis align-self:
- align-
  - center, start and end

## Border:
used with rem values from 0 to 4 and worked with for 2 corners ata time
- top (top left and right)
- bottom (bottom left and right)
- left (left top and bottom)
- right (right top and bottom)



## Githack Clone link:
* [Production](https://rawcdn.githack.com/NewIncome/mv_framework/b1cfb3e2ecbe3193fe6d7c0096fb541def15fcd0/index.html)

* [Development](https://raw.githack.com/NewIncome/mv_framework/feature/index.html)



For more info, check the [Odin Project](https://www.theodinproject.com/courses/html5-and-css3/lessons/design-your-own-grid-based-framework)


## Collaborators & profiles link:
- Allison Peres - [GitHub](https://github.com/alissonperes)
- J.Alfredo Cardenas - [GitHub](https://github.com/newincome)
