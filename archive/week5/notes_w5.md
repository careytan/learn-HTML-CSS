## Objectives
- I can create a grid using flex-box
- I can apply zindex, transition, and box shadows to my css
- I can use github pages to host my personal website.
- I can create an amazing personal website working from wireframe to final code. 

## Do Now
- Take the code for a simple grid in the DoNow folder. Don't touch the html!
- Use flex to make a 4 x 3 grid
- make the first grid element a perfect circle without touching the html!
- when you hover over the elements, make them change color.

```css
.wrapper{
	width: 850px;
	padding:12.5px 0 0 12.5px;
	background-color: #eee;
	
	display: flex;
	flex-wrap: wrap;
}

.gi{
	margin-right: 12.5px;
	margin-bottom: 10px;
	width: 200px;
	height: 200px;
	background-color: #8822FF;
	
	
}

.gi:hover{
	background-color: #22FF22;	
}

.gi:first-child{
	border-radius: 50%;
}

.gi:hover{
	background-color: #22FF22;
}
```

Introduce Transitions
-add to gi
```css
	transition: background-color 2s ease-out;
	transition: border-radius 2s;
	/*transition: background-color 2s;*/

```

## Clearfix
-Show a better clearfix problem/solution
-float the logo left or right
-What happens?
```
.clearfix:after { 
   content: "."; 
   visibility: hidden; 
   display: block; 
   height: 0; 
   clear: both;
}
```

## Z-index
- Think cartesian coordinates, what would z represent?
- This is the stacking order of elements on the page.
- load example, what do you notice?
- positive numbers will make the element move up
- negative numbers will make it move down
- nothing can go behind the body!

### You Do
- Open zindez/ex folder
- No need to edit the html!
- use zindex to move your least favorite simpsons character behind the orange div
- use zindex to put your favorite characters on top of all the others
- can you make the image that the mouse is over come to the front?
- BONUS, use hover to change the size when you hover over an image, can you make this happen smoothly?

Exercise Solution
```
.wrapper{
	width: 900px;
	height: 400px;
	margin: 0 auto;
	padding-top: 50px;
	padding-left: 200px;
	background-color: orange;
}

img{
	position: relative;	/*zindex only works with postioned elements*/
	height: 300px;
	margin-left: -100px;

	transition: height 1s;
}


/*character I don't like*/
.nelson, .burns, .maggie{
	z-index: -100;
}

img:hover{
	z-index: 100;

	height: 600px;
}
```

## Box shadow
- This is so hot right now
- google cards
- add this to zindex code

```css
box-shadow:10px 10px 10px #aaa;
```
- change the zindex, looks bad!
```css
box-shadow:10px 10px 10px rgba(0,0,0,0.1);
```
-better, describe rbga colors

## Github Page For Hosting!
- Create a new repo, named username.github.io
- initialize with a readme
- You html page must be called index.html
- Add your index.html and css files to the repo
- Go to `http://username.github.io/` should work

## Wireframes and Prototypes
**Purpose of wireframes** 
- layout of a page
- No style just visual structure
- The whole point is to have a quick way of playing with a sites design
- size the page to the device you are playing for

**Wireframe Options**
- Can be drawn by hand (this is usually where I start)
- Using google drawings and sheets, with stencils
- Using sketch, adobe illustrator or photoshop (obviously you will need a foundation in these programs)

**From wireframe to prototype**
- a prototype is a quick mockup of a website.
- allows us to test the site without writing any code.
- Usually a prototype has a buttons as links to a few different pages
- allows you as a designer to test some of the navigation and layout elements. 
- Prototypes can be tested with users, 
	+ ask a user to perform a specific task, 
	+ watch them as they interact with your prototype.

**Prototype Options**
- Protoyping on Paper, website and app
- Using Google Drawings and Sheets
- Using InVision, you will need to upload images or design files (psd, ai, pdf, sketch)

### Your Task
- Create a wireframe for the desktop version of your personal site.

## HW
- Make the best website that you can.
- Use github pages to host
- Have fun with this!