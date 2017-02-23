# Week 2 - Elements of Design

## Objectives

## Getting Started
- find the errors in the code

## Introduction to Design
There are basic design principles that are commonly discussed.
- Balance
  + Balance is an equal distribution of weight. In terms of graphics, this applies to visual weight.
- Unity
  + Unity helps all the elements look like they belong together. Readers need visual cues to let them know the piece is one unit-the text, headline, photographs, graphic images, and captions all go together.
- Contrast
  + Contrast occurs when two elements are different. The greater the difference the greater the contrast. The key to working with contrast is to make sure the differences are obvious.
+ Contrast can be created with size, position, and color.
- Repetition and Rhythm
  + Rhythm is a pattern created by repeating elements that are varied. Repetition (repeating similar elements in a consistent manner) and variation (a change in the form, size, or position of the elements) are the keys to visual rhythm.
- Direction and Movement
  + Direction is the way to lead the viewer’s eye through your design layout or composition.
- Economy
  + If you can remove an element within a design and that design still works, then you’ve practiced economy in design.
- Emphasis
  + Emphasis is what stands out or gets noticed first. Every layout needs a focal point to draw the readers eye to the important part of the layout.
- Scale and Proportion
  + Proportion refers to the relative size and scale of the various elements in a design. The issue is the relationship between objects, or parts, of a whole.

## Mini-lesson 1, Color
At the most basic level it is the interaction of colors in a design through complementation, contrast, and vibrancy.

Primary colors are used as the basis for all colors.

On the web, we use red green and blue for the basis of all colors. These are expressed by either rgb or hex values.

There are 4 basic color schemes that designers use.
- Triad
- Split Complimentary
- Analogous
- Monochromatic

Just like with typography, colors can tell a story.
- Think about your audience.
- What feelings do you want to convey?
- Colors can draw attention to elements and create emphasis.

### Live Code
- Show how to apply color as an rgb and hex value

### Exercise
Tell a story using a color scheme.
- Remix this [page](https://thimbleprojects.org/awdriggs/200681)


## Resources
- [Coolors](https://coolors.co)
- [Adobe Color](https://color.adobe.com/)

## Mini-lesson 2, Typography
Typography is the visual component of the written word. Good Typography keeps you reading.

There are two major typeface styles, serif and sans-serif

But, choosing a website is more nuanced than just choosing between two font styles. This is what you should considering when styling text.
- size
  + The width of each character is known as the 'set width', which spans the body of the letter plus a space that acts as a buffer with other letter
  + The height of each character is known as its 'x-height' (quite simply because it's based on the letter 'x'). When pairing two fonts a general rule is to choose fonts with a similar x-height.
- leading
  + Leading is vertical space between lines of text.
  + For legible body text that's comfortable to read, a general rule is that your leading value should be greater than the font size; anywhere from 1.25 to 1.5 times.
- Tracking and Kerning
  + Tracking is the space between all characters
  + Kerning is adjusting the space between specific characters.
- Measure
  + The width of a block of text.
- Hierarchy and Scale
  + If all type was the same size, then it would be difficult to know which was the most important information on the page. In order to guide the reader, then, headings are usually large, sub-headings are smaller, and body type is smaller still. Size is not the only way to define hierarchy – it can also be achieved with colour, spacing and weight.
- [Cheat Sheet](http://reference.sitepoint.com/css/typography)
- [Cheat Sheet 2](http://adamschwartz.co/magic-of-css/chapters/5-typography/)
- [Good Resource](http://learn.shayhowe.com/html-css/working-with-typography/)

### Live Code
- Show how to add a font from google font.
- Show how to apply in thimble
- Show how padding and margin work

### Exercise - 10 min
[Typography Exercise](https://thimbleprojects.org/awdriggs/200137)
- Don't worry about the html, only change the css
- Follow the comments.


## Mini-Lesson 3, Layout
Design Patterns
-show common design patterns

### Live Code
- [Starter Code](https://thimbleprojects.org/awdriggs/201334)
- HTML is done
- Add to the CSS

```css
#container{
  width: 800px;
  margin: 0 auto;
  height: 30px;
}

header{
  height: 60px;
  background-color: #33A1FD;
}

sidebar{
  background-color: #F55536;
  float: left;
  width: 300px;
  height: 400px;
}

main{
  float: right;
  width: 500px;
  height: 200px;
  background-color: #F79824;
}

footer{
  height: 200px;
  background-color: blue;
  clear: both;
}
```

### Layout Exercise
- Intro wireframes
- Have students choose a site, do a wireframe of that site.
- [ex + hw template[(https://docs.google.com/document/d/1t-bbm5FXT4a99HKeyhlICLdSv_OSBQmkxbhlKoD1KyU/edit?usp=sharing)


### Resources
[Web Design Principles](http://learndesignprinciples.com/index.html)
[Smashing Mag: Design Principles](https://www.smashingmagazine.com/2015/06/design-principles-compositional-balance-symmetry-asymmetry/)
[AirBnb Design Post](http://airbnb.design/building-a-visual-language/)
[12 Web Design Patterns](https://www.uxpin.com/studio/blog/web-layout-best-practices-12-timeless-ui-patterns-explained/)