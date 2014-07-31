# Khan Academy
## Text and Strings

### Text

+ Anytime you want to use text- use " "
+ text("hello", 30, 40);
	 
	
### String
+ String = Text
+ example:
	
		fill(92, 24, 219);
		var howBig = 30;

		var draw = function() { 
		howBig = howBig + 1;
		textSize(howBig);
		background(0, 238, 255);
    
		var myName = "Sophia";
		var message = myName + "!!!";
		text(message, mouseX, mouseY);}
		
## Functions
>#### <i>Function:</i><br>
> ##### Collection of code that is grouped together to make more useable<br>
> ` var "name" = function( ){      }`

### Examples

+ random(betweenThis#, andThis#) 
+ mouseX, mouseY [coordinates of mouse position]

### Function Parameters

<b>: Define variable in function name instead of in function</b>

		EXAMPLE: var drawMole = function(moleX, moleY){}
		
### Function Return Values


 EXAMPLE:
 		
	var calcTotalDonuts = function(numYears) 
	{return 3 * 365 * numYears;};

	fill(255, 0, 0);
	text("2-year-old Winston:", 10, 20);
	text(calcTotalDonuts(2), 10, 40);
	
### Global Functions
> :Special functions that are pre-defined



#### Transforms

* rotate(angle)
* scale(amount)

#### Environment

* width/height
		- size of canvas
* loop()/ noLoop()
		- start and stop drawing
* frameRate(fps)
		- change frame rate of draw
		
#### Mouse

* mouseX, mouseY
	 	- coordinates of the mouse
* pmouseX, pmouseY
		- past coordinates of mouse
	 
* var mouseClicked = function()
		- called when mouse is clicked
* var mousePressed = function()
		- called when mouse is pressed
* var mouseRelased = function()
		- called when mouse is released
* var mouseMoved = function()
		- called when mouse is moved
* var mouseOver = function()
		- called when mouse moves over canvas (like :hover)
* var mouseOut = function ()
		- called when mouse moves out of canvas

#### Keyboard

* key
		- number representing which key is pressed
* keyCode
		- when a special key pressed
* keyIsPressed
		- true if pressed, false otherwise
* var keyPressed = function()
		- called when a key is pressed
* var keyReleased = function ()
		- called when a key is released
* var keyTyped = function()
		- called when a key is typed

#### Math

* random(low, high)
		- generates a random number
* dist(x1, y1, x2, y2)
		- distance between two points
* constrain(value, min, max)
		- constrains value between two numbers
* max(num1, num2)
		- return the max of two numbers
* abs(num)
		- absolute value of number
...ect...

#### Date and Time

* day()/month()/year()
		- current date
* hour()/minute()/second()
		- current time
* millis()
		- milliseconds elapsed since program start
#### JavaScript

* if (x < 20){...}
		- only run if certain condition is true
* while (x < 250){...}
		- only run while certain condition is true
* for (var i=0; i < 8; i+ = 1){}
		- repeat fixed number of times
* var array = [0, 1, 2, 3, 4];
		- make an array of 5 numbers

### Local and Global Variables

 Local Variable
>: When variable is defined inside a function

Global Variable
>: When a variable is used outside a function




