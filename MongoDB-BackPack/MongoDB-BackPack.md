## Top 15 Interview MongoDB Questions

### What is MongoDB?
<p>MongoDB is an open-source non-relational document database. We can store data as JSON. That is why query data is so fast.</p>

### What are the collection and documents in MongoDB? 
<p>Collection: MongoDB database store data in the collection, like a table in a Relational database.</p>
<p>Document: a collection holds one or more BSON documents. Each document has one or more fields like Relational database columns.</p>

### What is a BSON document?
<p>MongoDB store data as a BSON document. BSON is a binary representation of a JSON document. It contains more data types than JSON.</p>

### What is ObjectId in MongoDB? 
<p>The object is a unique, small, 12-byte BSON type. The First 4 bytes represent the Unix timestamp, then 3 bytes represent the machine ID on which MongoDB is running. Then 2 bytes represent the process ID, and finally, 3 bytes represent the increment of the object ID.</p>

### What is the disadvantage of MongoDB? 
<p>Join is not supported</p>
<p>Limited documents size which is not more than 16 MB</p>
<p>We can not perform nesting documents for more than 100 levels</p>

