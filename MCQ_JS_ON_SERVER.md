### **Easy Level (10 Questions)**
**Question 1:**
What is Node.js primarily used for?
a) Styling web pages
b) Running JavaScript on the server-side
c) Creating databases
d) Managing network security
**Answer:** b) Running JavaScript on the server-side
---
**Question 2:**
Which command is used to run a JavaScript file named `app.js` using Node.js?
a) node app
b) node app.js
c) run app.js
d) start app.js
**Answer:** b) node app.js
---
**Question 3:**
Which Node.js module is used for file operations?
a) http
b) url
c) fs
d) path
**Answer:** c) fs
---
**Question 4:**
How do you import the FS module in a Node.js file?
a) import fs from 'fs';
b) require('fs');
c) const fs = require('fs');
d) import 'fs';
**Answer:** c) const fs = require('fs');
---
**Question 5:**
What is the correct syntax to read a file asynchronously in Node.js?
a) fs.readFileSync('file.txt', 'utf8');
b) fs.read('file.txt', 'utf8', callback);
c) fs.readFile('file.txt', 'utf8', callback);
d) fs.readFile('file.txt', 'utf8');
**Answer:** c) fs.readFile('file.txt', 'utf8', callback);
---
**Question 6:**
Which method is used to write data to a file in Node.js?
a) fs.writeFileSync
b) fs.writeData
c) fs.createFile
d) fs.writeFile
**Answer:** d) fs.writeFile
---
**Question 7:**
What will the following code output if `example.txt` contains "Hello World"?
```javascript
fs.readFile('example.txt', 'utf8', (err, data) => {
  console.log(data);
});
```
a) Error
b) undefined
c) Hello World
d) data
**Answer:** c) Hello World
---
**Question 8:**
What is the purpose of the callback function in `fs.readFile`?
a) To specify the file encoding
b) To handle the file data or errors after reading the file
c) To write data to the file
d) To close the file after reading
**Answer:** b) To handle the file data or errors after reading the file
---
**Question 9:**
Which of the following is true about Node.js?
a) It can only run on Windows.
b) It uses the V8 JavaScript engine.
c) It cannot handle asynchronous operations.
d) It is primarily used for styling websites.
**Answer:** b) It uses the V8 JavaScript engine.
---
**Question 10:**
Which file extension is commonly used for JavaScript files?
a) .js
b) .java
c) .node
d) .script
**Answer:** a) .js
---
### **Medium Level (10 Questions)**
**Question 11:**
How can you handle errors in an asynchronous `fs.readFile` operation?
a) Using try-catch blocks
b) Checking the error argument in the callback function
c) Errors cannot be handled
d) Using the throw statement directly
**Answer:** b) Checking the error argument in the callback function
---
**Question 12:**
Which method reads a file synchronously in Node.js?
a) fs.readFile
b) fs.readFileSync
c) fs.readFileAsync
d) fs.readSync
**Answer:** b) fs.readFileSync
---
**Question 13:**
What is the purpose of the 'utf8' argument in the `fs.readFile` method?
a) To specify the file path
b) To specify the encoding of the file content
c) To specify the file permissions
d) To specify the callback function
**Answer:** b) To specify the encoding of the file content
---
**Question 14:**
Which command can be used to check the version of Node.js installed on your machine?
a) node -v
b) node version
c) node --version
d) Both a and c
**Answer:** d) Both a and c
---
**Question 15:**
What does `fs.writeFileSync` do if the file does not exist?
a) Throws an error
b) Creates the file and writes data to it
c) Logs a message to the console
d) Skips the write operation
**Answer:** b) Creates the file and writes data to it
---
**Question 16:**
How do you ensure that a file is read synchronously using the FS module?
a) Use `fs.readFileSync`
b) Set a flag in `fs.readFile`
c) Use `fs.read`
d) Add `async` before `fs.readFile`
**Answer:** a) Use `fs.readFileSync`
---
**Question 17:**
What is the output of the following code if `example.txt` contains "Hello World" and the file does not exist?
```javascript
const fs = require('fs');
try {
  const data = fs.readFileSync('example.txt', 'utf8');
  console.log(data);
} catch (err) {
  console.error(err);
}
```
a) undefined
b) Hello World
c) Error: ENOENT: no such file or directory
d) No output
**Answer:** c) Error: ENOENT: no such file or directory
---
**Question 18:**
Which of the following is a built-in module in Node.js?
a) express
b) mongoose
c) fs
d) lodash
**Answer:** c) fs
---
**Question 19:**
How can you make a function asynchronous in Node.js?
a) Using the `async` keyword
b) Using the `await` keyword
c) Using callbacks, promises, or async/await
d) Node.js functions are asynchronous by default
**Answer:** c) Using callbacks, promises, or async/await
---
**Question 20:**
Which of the following is the correct way to handle multiple asynchronous file read operations?
a) Using nested callbacks
b) Using Promises or async/await
c) Using synchronous methods
d) Using setTimeout
**Answer:** b) Using Promises or async/await
---
### **Hard Level (10 Questions)**
**Question 21:**
Which method can be used to append data to a file in Node.js?
a) fs.appendFileSync
b) fs.appendFile
c) Both a and b
d) fs.writeFile with append flag
**Answer:** c) Both a and b
---
**Question 22:**
What will happen if you use `fs.writeFile` to write to an existing file?
a) The file will be appended with new data.
b) The file will be overwritten with new data.
c) An error will be thrown.
d) The write operation will be ignored.
**Answer:** b) The file will be overwritten with new data.
---
**Question 23:**
How can you read a directory's contents in Node.js?
a) fs.readDir
b) fs.readDirectory
c) fs.readdir
d) fs.listFiles
**Answer:** c) fs.readdir
---
**Question 24:**
What is the purpose of `fs.existsSync` in Node.js?
a) To read a file
b) To check if a file or directory exists
c) To delete a file
d) To write to a file
**Answer:** b) To check if a file or directory exists
---
**Question 25:**
In Node.js, how can you create a new directory?
a) fs.mkdir
b) fs.createDirectory
c) fs.newDirectory
d) fs.createDir
**Answer:** a) fs.mkdir
---
**Question 26:**
What will the following code snippet output?
```javascript
const fs = require('fs');
console.log('Start');
fs.readFile('example.txt', 'utf8', (err, data) => {
  if (err) throw err;
  console.log(data);
});
console.log('End');
```
a) Start End Hello World
b) Start Hello World End
c) Hello World Start End
d) End Start Hello World
**Answer:** a) Start End Hello World
---
**Question 27:**
Which of the following statements about asynchronous file operations in Node.js is true?
a) They block the execution of subsequent code until the operation is complete.
b) They allow other code to run while waiting for the operation to complete.
c) They are slower than synchronous operations.
d) They are deprecated in modern versions of Node.js.
**Answer:** b) They allow other code to run while waiting for the operation to complete.
---
**Question 28:**
How do you handle multiple asynchronous operations without falling into "callback hell"?
a) Use synchronous methods
b) Use nested callbacks
c) Use Promises or async/await
d) Avoid asynchronous operations
**Answer:** c) Use Promises or async/await
---
**Question 29:**
What does the `utf8` parameter specify when used in `fs.readFile`
 and `fs.readFileSync` methods?
a) The file path
b) The encoding format of the file
c) The size of the file
d) The permissions of the file
**Answer:** b) The encoding format of the file
---
**Question 30:**
Which method is used to rename a file in Node.js?
a) fs.rename
b) fs.renameFile
c) fs.changeFileName
d) fs.move
**Answer:** a) fs.rename
---
