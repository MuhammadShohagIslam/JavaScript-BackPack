### What is Node.js? 
<p>Node.js is a open source, cross-platform, JavaScript runtime environment. As a backend developer we can use Node.js for making server side application</p>


### Where can you use Node.js?
<p>When we decide that we want to make a application, which one like data-intensive application, we can use Node.js because Node.js is the perfect match for data-intensive application.</p>
<p>We are not only use Node.js for making I/O intensive application, but we can use real time application, Network application, E-Commerce application</p>

### Is Node.js perfect use for making every application?
<p>No, If we want to make heavy computational task like application, Node.js is not perfect</p>
<p>Relational Database is not best suit for Node.js</p>
<p>If we want to make application where heavy CPU-intensive operations or task, Node.js is not the best option </p>

### How would you define the term I/O?
<p>I/O is the reading / writing file or operation or a communication that data transfer one media to another media. Media can be a physical device,  network.</p>

### What is NPM?
<p>Node package manager which is responsible for managing whole application package file and module in node.js. it has some command line that help to install file update or delete and control versioning.</p>

### What are the modules in Node.js?
<p>Module is like a package where one or more javascript file organized which can be used whole application just we need require  Function with the parenthesis if we is not import file system. Some module name are fs, path,  http and so on.</p>

### What are some of the most commonly used libraries in Node.js?
<p>Express.js: express js is minimal and perfect node js framework which has robust set of features through which we can create back end application with node.js.</p>
<p>Mongoose: mongoose is a object data modeling  (ODM)  library for node.js and mongodb which help to create schema based model and connecting database with node.js.</p>

### What does event-driven programming mean? 
<p>Event drive ln programming is a computer paradigm where approach uses event to trigger various functionality. One of the example, callback function,  a callbackfunction is called when a event is triggered.</p>

### What is an Event Loop in Node.js?
<p>Event loop is the most important environment features in node.js through which handle all of the asynchronous callback and it is the fundamental of non blocking input/output in node.js<p> 


### How does work Node.js?
<p>Let's talk about step by step Node.js<p>
<ul>
    <li>When client request a node.js server to interact with web server application, request can be non-blocking(asynchronous ) or blocking(synchronous ).This request can be for query for data, update the data, delete the data, </li>
    <li>Client side request when hit node.js, Node.js received the client request, and then Node.js send this request to the Event-Queue<li>
    <li>Through Event-loop, all of the request passed one-by-one and also non-blocking simple request processed by the event-loop and return the response to the corresponding client</li>
    <li>Through single thread pool which  all of the blocking operation passed one-by-one like file system, database, then when complete all of the work, response send to the event-loop, finally response go to the client  </li>
</ul>

### Why is Node.js Single-threaded?
<p>In my opinion, Node.js single threaded because javascript is single thread language.Single-thread means it has only one call-stack. Node.js single-thread but it maintain multi-threaded work with callback or asynchronous system</p>

### If Node.js is single-threaded, but how does it handle concurrency?
<p>Since Node.js single-threaded, but it has asynchronous nature and Event-loop through which Node.js handle concurrency</p>

