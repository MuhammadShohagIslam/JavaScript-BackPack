### What is an event loop in JavaScript?

<p>The Event Loop is the mechanism for this reason we are saying javascript is an asynchronous language. Javascript executes all of the operations with a single thread, but we can get multi-thread flavor through the event loop. When we execute all of the javascript code, which does some step: </p>
<ul>
    <li>Since js code read line by line and every js operation function to go call stack, but if any asynchronous code has js codes, it goes firstly Call Stack to WEB API in the browser, after finishing all of the work, this operation to go event queue, then through event loop, the operation to go call stack, then finally this operation executed.</li>
</ul>

### What is the difference between setTimeout vs setInterval?
<p>setTimeout and setInterval are the javascript method which are the solution to run our code asynchronously</p>
<p>setTimeout execute once, but it can be used recursively to wait for a call stack to indicate it should wait to execute again. setInterval will execute continuously over a specific amount of time.</p>
