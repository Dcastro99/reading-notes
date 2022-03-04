# **CSS Transforms, Transitions, and Animations**

> ## Readings: Article on CSS Transforms

- Transforms is a way to positiona dn alter elements with CSS.

- You can use the ***transform*** property to achieve this. It can alter things in 2D or in 3D.

- in this article found https://learn.shayhowe.com/advanced-html-css/css-transforms/

they give the example of

```CSS
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

- selecting multiple vendors will have a better chance of your effect working in any browser since not all support it.

You have transform : scale, rotate, or you can combine them. 

> ## Readings: Article on CSS Transitions & Animations

- Transitions are very exciting.  Theycan determine a duration of some effect that you're placing on an element.

- An example can be found on https://learn.shayhowe.com/advanced-html-css/transitions-animations/ in which they describe how one can change the box  background color over the course of 1 second in a linear fashion:

```CSS
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
```

- you can also have an element move from side to side of your screen at a speed you'd like it transitioning in.

- 8 important CSS transitions to know
  * 1 - Fade in
  * 2 - Change color
  * 3 - Grow & shrink
  * 4 - Rotate elements
  * 5 - Square to circle
  * 6 - 3D shadow
  * 7 - Swing
  * 8 - inset border

- example from https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users

```CSS
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}
```
