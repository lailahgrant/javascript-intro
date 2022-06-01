# JAVASCRIPPT INTRO
`Introduction topics to JavaScript`

> Prerequisites
>- Understanding of HTML and CSS

> What is JavaScript?
> It is a :
> - Client-Side Scripting Language - JS is executed only on the client-side (no server execution) [everything will execute on the client and the performance will be better.]
> - It is interpreted by browser's javascript engine.
>   -  e.g how's HTML runs on  browsers?
>       - Every browser has a `parser` which read the HTML tags and renders the text accordingly.
>   - What of JS?
>       - Every browser has a JS Engine e.g Chrome has a V8 engine, etc.
> - It is `untyped`, multi paradigm, functional, event driven. [untyped - no datatype specification needed on variable creation.] [functional - can split code into modular, make code into many functions to be used when needed].

> Advantages of JavaScript
> - Less Server interactions.
> - Better performance.
> - Increased Interactivity.
> - Richer interface [animations, Dynamic CSS]

> #### JavaScript Arrays
> - They let us store multiple values in a single variable.
> - They store a fixed size of sequential collection of elements.
> - Need to pass the `index` in order to access an element.
> - `index` starts from `0`.
> 
> ##### Writing Array Data
> - var fruits = new Array("apple", "mango", "orange");  OR
> - var fruits = ["apple", "mango", "orange"];
> `new - special keyword to allocaTE fresh new memory space`
> ##### Reading Array Data
> - fruit[0] is the first element.
> - fruit[1] is the second element
> - fruit[2] is the third element
> 
> `Array is a collection of similar type.`
> `Arrays have a static memory allocation : - any particular number of values passed in array declaration is the size of the array. e.g Array below is of size 5.`
> `var arr = new Array(10,20,30,50,40,50)`

###### Array Sort and Search
* - If there are a number of elements in an array
*  BubbleSort e.g for sorting in an order ( ascending or descending order)

##### Variables
>* Used to store data temporarily.
>* Variables will not have specific data type in JS
>* Variables can have global or local scope (for functions mostly).
>* e.g var name ="Lailah", age=19, salary = 5000.23;

##### Conditional Statements
> * if...else...
> * Switch
> `if...else Flowchart`
<img >

> Switch
> * To execute menu-like programs
> * Use `case` keyword.
> <img>


##### Iteration Statements (Loops)
> * Executes set of statements several times
> * Keeps on executing until gives condition is true
> * Different control statements can be nested
>
> ###### Loops Classifications.
> * for
> * while
> * do..while
> <img>
> - - for loop - used when the number of iterations or executions are known.
> >Syntax
> `for (init; condition; increment)`
> `{`
> `conditional code;`
> `}`
> <img>
> - - while loop - repeatedly executes statements as long as the given condition is true.
> >Syntax
> `while(condition)`
> `{`
> `conditional code;`
> `}`
> <img>
>  - - do.. while loop 
> * - - Checks the condition at the end of the loop execution
> * - - do... while loop guaranted to execute at least one time.
> * - - Used for user interactions like a user entering PIN once e.g. mobile money, Whatsapp code
> >Syntax
> `do`
> `{`
> `conditional code;`
> `}while(condition);`
> <img>

##### Operators
* It is a `symbol` which tells the system to perform specific operation.
* Javascript has rich collection of built-in data types
* Operators can be `unary(++,--), binary or ternary`.

###### Operators classifications.
* Arithmetic operator (+, -, /, *, %, ++, --, +=, -=)
* Assignment operator (=)
* Comparison operator
* Logical operator [&& Logical and, || Logical or, ! Logical not]
* Ternary operator [(condition) ? true : false]
<img>

###### Javascript animations.



















