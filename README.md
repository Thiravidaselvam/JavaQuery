# Scope functions-JavaQuery
basics of java query functions


# Differend type of scope

<Pre>
const name='I am trying to develope React function'
function print () 
{
	const name='it is called from function scope'
	console.log(name)
	if (true)
	{
	const name='it is called from block scope'
	console.log(name)
	}
}
console.log(name)
print()
	
</Pre>

 # Variable Scope function
<pre>
 function print()
 {
 	if (true)
  	{
   	var name='Test value of variable scope'
    	}
 }  
 print()
 console.log(var)

</pre>

above code name was declared in if block , if condition true then we can call name other wise create undefined error so it is called variable scope

# Hoisting  variable

<pre>
	function hoistcode()
	{
		a=10;
		let b=15;
	}
	hoistcode();
	console.log(a) // 10
	console.log(b) // undefined issue
</pre>

above a has declared within the block java has consider non declared varaible as var type so we can call out side of the function. let variable only we can use in the block error code: VM137:8 Uncaught ReferenceError: b is not defined
    at <anonymous>:8:14.
it is called hoisting.

 




     
