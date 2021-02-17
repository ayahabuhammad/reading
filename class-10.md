# Class 9 Reading

# Errors Handeling & Debugging


To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

execution contexts according to JavaScript interpreter uses this concept. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.


Each time a script enters a new execution context, there are two phases of activity:
      PREPARE
      EXECUTE

If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

# ERROR OBJECTS:
The try statement lets you test a block of code for errors.

The catch statement lets you handle the error.

The throw statement lets you create custom errors.

The finally statement lets you execute code, after try and catch, regardless of the result.

Errors Will Happen!
When executing JavaScript code, different errors can occur.

Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.

Example
In this example we have written alert as adddlert to deliberately produce an error:

\<p id="demo"></p>


\<script>

\try {

 \ adddlert("Welcome guest!");

\}
\catch(err) {

 \ document.getElementById("demo").innerHTML = err.\message;
\}

</script>

 Error objects can help you find where your mistakes are and browsers have tools to help you read them.

   Some of types of error objects
       - Type Error
       - RangeError
       - Error
        - NaN


# Debugging
Code Debugging
Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

JavaScript Debuggers
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.


Debugging is about deduction: eliminating potential causes of an error. You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.

If you know your code might fail, use try, catch, and finally. Each one is given its own code block.

