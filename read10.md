# Welcome To The Read10 Page...

![img](https://0701.static.prezi.com/preview/v2/h3j5rflrkheepc5js3m7tae7e76jc3sachvcdoaizecfr3dnitcq_3_0.png)

**There are 3 types of errors in programming:**

1. Syntax Errors : Occur at compile time in traditional programming languages and at interpretation time in JavaScript.

2. Run time Error : Also called exceptions, occur during execution (after compilation/interpretation).

3. Logical Error : Logic errors can be the most difficult type of errors to track down.

**The JavaScript debugger:**

*The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.*

![img](https://mdn.mozillademos.org/files/16239/firefox_debugger.png)

**Exception Handling:**

*Exception handling is accomplished with a try...catch statement. When the program encounters an exception, the program will terminate in an unfriendly fashion. To safeguard against this unanticipated error, we can wrap our code in a try...catch statement.*

*The try block must be followed by either exactly one catch block or one finally block (or one of both). When an exception occurs in the try block, the exception is placed in e and the catch block is executed. The optional finally block executes unconditionally after try/catch*

***Example:***

`var a = 100; `
`var b = 0; `
`try { `
  ` if (b == 0 ) { `
   `   throw(“Divide by zero error.”); `
 `  } else { `
   `   var c = a / b; `
  ` } `
`} `
`catch( e ) { `
 `  console.log("Error: " + e ); `
`}`


**The throw Statement:**

*Use the throw statement to throw an exception. When you throw an exception, you specify the expression containing the value to be thrown*

***Example:***

`<script type=”text/javascript”>`
   ` function doSomething()`
   ` {`
      `var a = 10;`
      `try` 
        `{`
          `if(a === 100)`
            `alert(“Value of variable a is : “ + a );`
          `else`
            `throw( “Divide by zero error.” ); `     
         `}`
      `catch ( e ) {`
        `alert(e);`
      `}`
    `}`
 `</script>`
`</head>`

**What are browser developer tools?**

*Every modern web browser includes a powerful suite of developer tools. These tools do a range of things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long they took to load.*


**How to open the devtools in your browser?**

*The devtools live inside your browser in a subwindow that looks roughly like this, depending on what browser you are using:*

![img](https://mdn.mozillademos.org/files/16205/DevTools_63_inspector.png)