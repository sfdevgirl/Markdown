# Object Oriented in JavaScript

### What is an object?
#### A collection of properties and methods

+ Unordered
+ Methods are the term used for functions dellared on the object
+ Properties are keys that return values

		var thisIsAnObject = {}; // Object Literal

		var thisIsAlsoOne = new Object(); // Constructor Method
	
### A key is the access point to properties and methods of an object
		var yGood = {pizza: 'true'};
		
### Methods are Functions attached to the Object
		yGood skyBlue = function(){ return 'the sky is blue';}
### The prototype
#### No class definer, instead we have the prototype

	Object.prototype && Object._proto_
 
	var oO = new Object(); var yLiter = 
	{}, oO.prototype // returns Object{} oO_proto_//returns Object{}

	yLiter._proto_//returns Object{}, 
	yLiter.prototype//return undefined...


### Object.create()
#### Shortcut method to create classes that inherit from others.

		function Animal(){this.legs = 4;}
		var Person = {legs:2};
		Person.prototype = 
		Object.create(Animal prototype);
		
### Why do proto?
#### To create classes. Reusable structures that can do things.

>The purpose of software is to abstract away complexity