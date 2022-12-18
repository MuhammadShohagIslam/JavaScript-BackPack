## Top 15 Interview Node.js Questions

### What is Node.js? 
<p>Node.js is an open-source, cross-platform, JavaScript runtime environment. As a backend developer, we can use Node.js for making server-side applications </p>


### Where can you use Node.js?
<p>When we decide that we want to make an application, which one like a data-intensive application, we can use Node.js because Node.js is the perfect match for data-intensive applications.</p>
<p>We not only use Node.js for making I/O intensive applications, but we can use real-time applications, Network applications, and E-Commerce applications </p>

### Is Node.js perfect use for making every application?
<p>No, If we want to make heavy computational tasks like applications, Node.js is not perfect</p>
<p>Relational Database is not the best suit for Node.js</p>
<p>If we want to make an application where heavy CPU-intensive operations or tasks, Node.js is not the best option </p>

### How would you define the term I/O?
<p>I/O is the reading/writing file or operation or communication that data transfer from one media to another media. Media can be a physical device or network.</p>

### What is NPM?
<p>Node package manager which is responsible for managing the whole application package file and module in node.js. it has a command line that helps to install file updates or delete and control versioning.</p>

### What are the modules in Node.js?
<p>Module is like a package where one or more javascript files are organized which can be used for the whole application just we need to require a function with the parenthesis if we are not importing the file system. Some module names are fs, path,  HTTP, and so on.</p>

### What are some of the most commonly used libraries in Node.js?
<p>Express.js: express js is a minimal and perfect node-js framework that has a robust set of features through which we can create back-end applications with node.js.</p>
<p>Mongoose: mongoose is an object data modeling  (ODM)  library for node.js and MongoDB which helps to create the schema-based model and connect the database with node.js.</p>

### What does event-driven programming mean? 
<p>Event drive programming is a computing paradigm where the approach uses events to trigger various functionality. One of the example, callback functions, the callback function is called when an event is triggered.</p>

### What is an Event Loop in Node.js?
<p>Event loop is the most important environmental feature in node.js through which handle all of the asynchronous callback and it is the fundamental of non-blocking input/output in node.js<p> 


### How does work Node.js?
<p>Let's talk about step-by-step Node.js<p>
<ul>
    <li>When a client requests a node.js server to interact with a web server application, the request can be non-blocking(asynchronous ) or blocking(synchronous ). This request can be for a query for data, update the data, delete the data, </li>
    <li>Client side request when hit node.js, Node.js received the client request, and then Node.js send this request to the Event-Queue<li>
    <li>Through Event-loop, all of the requests are passed one by one and also non-blocking simple requests are processed by the event loop and return the response to the corresponding client</li>
    <li>Through a single thread pool all of the blocking operations are passed one-by-one like file system, and database, then when complete all of the work, the response is sent to the event loop, and finally response goes to the client  </li>
</ul>

### Why is Node.js Single-threaded?
<p>In my opinion, Node.js is single-threaded because javascript is a single-thread language. Single-thread means it has only one call stack. Node.js single-thread but it maintains multi-threaded work with a callback or asynchronous system</p>

### If Node.js is single-threaded, how does it handle concurrency?
<p>Since Node.js is single-threaded, it has asynchronous nature and Event-loop through which Node.js handle concurrency</p>

### What are Callbacks in Node.js?
<p>Callback is a function called when the task is completed. It is an important feature that allows other code to run in the meantime and helps prevent blocking.</p>

### What is an EventEmitter in Node.js?
<p>It is a class that holds all of the objects. Through EventEmitter, we can emit events.</p>

### What is the package.json file?
<p>It is the most essential file among the node.js file because it holds all of the information of our project, version controlling, metadata of our application, and store all of the dev and dependency</p> 