# Top 15 JavaScript Question

### How Does Browser Runs JavaScript?

<p>JavaScript is an interpreted language, which means before sending code to the browser we do not need to compile javascript source code. it takes to code and runs it. Every Browser uses a javascript engine, but they have their own javascript engine. such as the modern javascript engine name V8. Through which google chromo browser run javascript</p>

### How Does Browser Works?

<p>Browser is a one kind of desktop software that we are use with install</p>
<p>Firstly, browser collected whole html file like .html and css style lke .css, then convert HTML to DOM tree through HTML parser as well as CSS to style tree through CSS parser</p>
<p>DOM tree, style structure are attached together to make render tree which internally make layout, if we change or update anything, it is automatically re-rendering</p>
<p>After completing render tree process , we can see the actual UI, it's called paint to display!</p>

### What's the difference between HTTP vs HTTPS ?

<P>HTTP is a protocol through which it is fetching resources such as HTML document, javascript file, image file and so on.Through HTTP,any type of data are  exchanged. IT is a client-server protocol</P>
<p>HTTP has lack security mechanism which is not encrypt text which use plain text, whereas https is high secure because it's provide SSL or TSL digital certificate to secure communication client to server </p>
<p>HTTP operates at the Application layer, HTTPS operates Transport layer</p>
<p>HTTP is the fast, but HTTPS work with slow because</p>

### What is an event loop in JavaScript?

<p>The Event Loop is the mechanism for this reason we are saying javascript is an asynchronous language. Javascript executes all of the operations with a single thread, but we can get multi-thread flavor through the event loop. When we execute all of the javascript code, which does some step: </p>
<ul>
    <li>Since js code read line by line and every js operation function to go call stack, but if any asynchronous code has js codes, it goes firstly Call Stack to WEB API in the browser, after finishing all of the work, this operation to go event queue, then through event loop, the operation to go call stack, then finally this operation executed.</li>
</ul>

### What is the difference between setTimeout vs setInterval?
<p>setTimeout and setInterval are the javascript method which are the solution to run our code asynchronously</p>
<p>setTimeout execute once, but it can be used recursively to wait for a call stack to indicate it should wait to execute again. setInterval will execute continuously over a specific amount of time.</p>

### What are Javascript Cookies?
<p>Javascript cookies are the client database, where we can store data or any information as a string</p>

### What is the difference between local storage vs session storage?
<p>Both of store data in our computer browser</p>
<p>The key difference is that local storage data is not deleted if you can not clear the local storage data and will not delete data after close the browser</p>
<p>Session Storage data are removed when we close the browser</p>