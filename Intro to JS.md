#Khan Academy
##Intro to JS: Drawing and Animation

+ ###<u>Drawing</u>

		
	* 	Rect

		(x, y, w, h);
	* 	Ecllipse

		(x, y, w, h);
	* 	Line

		(x1, y1, x2, y2);
	* 	Triangle

	 		(x1, y1, x2, y2, x3, y3);
	 		
	* 	Point

	 		(x, y);
	 		
	* 	Image

	 		(image, x, y, w, h);
	 		
	* Arc
			(x, y, w, h, start, stop);
			
x-coordinate of the center of the complete ellipse derived from the arc. y-coordinate of the center of the complete ellipse derived from the arc. width of the complete ellipse formed by the partial arc. height of the complete ellipse formed by the partial arc. angle to start the arc at. angle to stop the arc at
	
+ ###Coloring
*Color function goes before shape function* 

	*  nostroke();
	*  no outline
	*  stroke(r,b,g);
	*  outline color
	*  fill(r,b,g);
	*  fill color

+ ###Variables

 *Expressions: Making variables relative to one another*

	
> A variable is a way to store values. To use a variable, we must both "declare" it, to let the program know about the variable, and then we must "assign" it, to let the program know what value we are storing in the variable.
	
	var [name] = [value];
	[attribute](#, #, [name], [name])
	Always define variable before use

*How can we pick names for our variables?*
> For variables in JavaScript, follow these rules:

 * <b>Variable names should begin with letters, `$` or `_` and only contain letters, numbers, `$` and `_`</b>
 	
	* Variable names are **case sensitive** - that means that "xPos" is different from "xpos", so make sure you are consistent with how you type it.
	
	* Variable names can't be the same as existing variable names, and there are a lot in our ProcessingJS programming environment. If you ever see an error pop up like "Read only!", try changing your variable name.
	
	* Variable names should be clear and meaningful - for example, instead of "ts", use "toothSize".
	
	* Variable names should use "camel case" for multiple words, like "toothSize" instead of "toothsize" or "tooth_size".

+ ###<u>Animation</u>
Function()
:	a loop; everything inside gets ran over and over again
	


	
