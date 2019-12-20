# Block-scope
The fundamentals of the different scopes available in JavaScript, the different scenarios that cause scopes to be created and the impact this has on variable access.
JavaScript has traditionally had two types of scope: global scope and function scope, and the place in your code in which a variable is declared affects whether it can be accessed by other parts of your code.

Consider a code

var globalVariable = 'This is global';

function globalFunction1() {
  var innerVariable1 = 'Non-global variable 1';
}

function globalFunction2() {
  var innerVariable2 = 'Non-global variable 2';
}

LOOPING AND RECURSION
/*looping using for loop*/
for(let i=0;i<5;i++)
{
  console.log(i)
}
/*looping using recursion*/
let x = 0;
function recurse(){
console.log(x);
  x++;
	  if(x<11){
		  recurse();  
  }
}
recurse();
