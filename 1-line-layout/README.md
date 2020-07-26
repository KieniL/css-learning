# Tutorials from one line layout

<https://youtu.be/qm0IfG1GyZU>

1. Super-center
**Always centered**
Define a div with this two css segments to let the body always stay responsive cented
    display: grid;
    place-items: center;

2. The deconstructed pancake
**Stretch childen based on width**
Define three divs in a parent div. Give the parent   display: flex; flex-wrap: wrap;
See the css for stretching of the children

3. Sidebar says
Defines a coloured sidebar which stretch to a max of 25%. This is achieved by grid-template-columns: minmax(150px, 25%) 1fr; in the body {}

4. Pancake stack
A stack (header, main footer) which stretches in width but don't be deconstructed like (2.)
Defines a header, main and footer segment.
In the body with this grid-template-rows: auto 1fr auto; the first and third div auto and the second is lfr

5. Holy Grail layout
Like pancake stack but with left and right sidebar.
The magic is done with grid-column: 1 / 4; and grid-template: auto 1fr auto / auto 1fr auto

6. 12 span grid
Write in body grid-template-columns: repeat(12, 1fr); to create 12 lfr. With this the other spans can got from 1/2 or 3/7

7. RAM (Repeat, Auto, Minmax)
With this in body   grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
There are repeats too but with a minmax frame

8. Line up
Responsive cards

9. Clamping My Style
Get a always cented div with a clamping size

10. Respect for Aspect
Always centered div with an aspect ratio
