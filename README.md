# CSS to the Rescue - Rubik's Cube

This is the process report for the CSS to the Rescue course. This course was given by the lecturers:

<li>Sanne 't Hooft</li>
<li>Nils Binder</li>
<li>Roel Nieskens</li>

## Assignment

The main goal of this course was to experiment with new CSS features and see what is possible to do with all CSS and no
JavaScript. In the first lesson we were given the four options to choose from. These were:

<ul>
    <li>Make a control panel</li>
    <li>Create a firework show</li>
    <li>Build a Rubik's Cube (Hard)</li>
    <li>Fold a paper plane (Hard)</li>
</ul>

For me the Rubik's Cube looked like a real challenge, so I was intrigued to go for the cube. I was not yet sure if it
would be doable. How cool would it be to be able to code your own working Rubik's Cube. One given requirement for
choosing one of the harder assignments was that you could solve a given math problem. Sanne 't Hooft gave me a fun math
problem to solve, and it went as follows:

"Two student just graduated and want to start working at a law firm. When they are at their job interview, the manager
gives them two options for payment: 1. Receive €80 every day; 2. Receive €0,01 on the first day and have it be
multiplied every next day."

Which is the better option to choose?

---

Since I had not really done any math for over 5/6 years, the problem was a bit harder for me than I hoped. One thing I
knew for sure was that the first option uses linear growth and the second options uses exponential growth. Since
exponential growth always becomes more in value faster that linear growth, this would definitely be the option to
choose. Now I really wanted to solve the problem by knowing how many days it would take for the second option to be more
lucrative than the first option.

Since math wasn't on my brain for the past years, I had to look up the formula to calculate exponential growth. It goes
like this:

``
f(x) = ab^x
``

[//]: # (FINISH THIS PART ABOUT MATH PROBLEM)

When I completed the math problem I was confident again about my mathematical ability. I was ready to take on the Cube!

## Process

These are the steps I took to make my Rubik's Cube:
<ol>
    <li>Build one single cube in 3D</li>
    <li>Control the cube using range inputs</li>
    <li>Build the full Rubik's Cube</li>
    <li>Rotate one side of the Rubik's Cube</li>
    <li><mark>.... More to come</mark></li>
</ol>

### Build a single cube in 3D

Before I started this assignment, I had no idea how to work with 3D in CSS. This is also one of the reasons why I chose
this assignment. The first step was to figure out how to make a cube in 3D. I found this website that gives an intro to
3D in CSS. Here I got introduced to perspective, 3D transform functions and making 3D objects. I followed the tutorial
all the way to learning how to create a cube in CSS. This course was really helpful for me. It instructed every step
very clearly and went in to detail of how 3D in CSS works.

To define a 3D CSS you're defining a space or a scene in which the 3D takes place. To do this the given element should
have a perspective applied. This can be done in two ways:

The first method is by using the perspective function

```css
.element {
    transform: perspective(400px);
}
```

The second method is by using the perspective property

```css
.element {
    perspective: 400px;
}
```

When you work with more than one element that needs the same vanishing point (perspective), the first functional option
doesn't work out well. Every element gets its own perspective applied and the elements don't line up together. For my
use case of making a cube every panel or side needs to have the same perspective. This means I will have to work with
the second notation. 

## Workshops

## Result

## Sources

<ul>
  <li>https://3dtransforms.desandro.com/</li>
</ul>
