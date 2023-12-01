Js is synchrouns single threaded 
<!-- Execution Context -->
<!-- Call stack execution : Global exeution context -->

<!-- Hoisting  variable and function hoisting. -->
Hoisting (Execution context & creation phase)

Hoisting as a core concept relies on the way how Execution Context is created. In the first phase i.e. the Memory Allocation Phase all the variables and functions are allocated memory, even before any code is executed. All the variables are assigned undefined at this point in time in the local memory.

<!-- let & const in JS 🔥Temporal Dead Zone  -->
LET CONST ARE TO DECLARE BLOCK SCOPED VARIABLES
When variables declared in let can be reassigned, 
they can’t be assigned if they were declared with const.

Let and VAR DIFFERENCE
Scope of let is block level we usually use them when there is a limited use of those variables
Such as loops, while loop, inside loops, if condition
Var is used when value of variable need to be less change and used to access globally.

Var can be used to redeclare to some other value

Variable couldn’t be declared in let

Const you can’t change once it’sdecalred (read only reference)
With const you can declare local variables with block scope rather than function scope


Var —> Cretes function scoped
Var —> global variable is attached to window object
Let const —> block scoped
<!-- const variable declaration and initialisation must be done on the same line. -->
<!-- There are three types of error: [1] referenceError {given where variable does not have memory allocation} [2] typeError {given when we change type that is not supposed to be changed} [3] syntaxError {when proper syntax(way of writing a statement) is not used}. -->

<!-- Callback Functions -->
Since Js is synchrounous to make it asynchrounous we can use callback.

asynchrounous operations: settimeout, 
1. Function that is passed on as argument to another function is called callback function.
2. setTimeout helps turn JS which is sinhlethreaded and synchronous into asynchronous.
3. Event listeners can also invoke closures with scope.
4. Event listeners consume a lot of memory which can potentially slow down the website therefore it is good practice to remove if it is not used.

<!-- Map, Filter, Reduce -->
1. map method is used when we want transformation of whole array.
2. filter is used when we want to filter the arrar to obtain required value.
3. reduce is used when we want to reduce the array to single value eg (max, min, avg, sum, difference etc).
4. reduce passes two arguments one function(which includes accumulator and initial value as argument itself) and another initial value of accumulator.

******************************************CSS***************************
<!-- Selectors -->
Element Selectors (h1,p)
Class Selectors (.)
Id selectors (#)
Group Selectors (h1,h2)
Universal Selectors (this selects everything) (*{})
!important overrides everything

<!-- Colors -->
color
rgb
rgba (Alpha) rgba(0,0,0,0.5)
hexa decimal color : #000000 #FFFFFF #00FFFF #0000FF #FF00FF 
hsla(hue, saturation, lightness, alpha)

<!-- /* Css Units & Sizes */ -->
