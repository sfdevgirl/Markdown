# Lecture Notes [8]

### Functional Programing


>**Callback Function**
> <br>also known as a higher-order function

>*: a function that is passed to another function as a parameter, and the callback function is called (executed) inside otherFunction.*

><i>Example: </i>

>`$("#btn_1").click(function() {
  alert("Btn 1 Clicked");
});`

<br><br>

#### Generate a random number between A and B


`var randAtoB = function(a,b){
var res = (a+(Math.random() * b-a );
return res;
}`