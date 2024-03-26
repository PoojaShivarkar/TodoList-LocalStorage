/*
the localStorage obaject allows you to save key/value pairs in the browser.
*/

//how to add the data from storage 
localStorage.setItem("javaScript","localStorage");

// how to get data from localStorage
localStorage.getItem("javaScript");

// how to remove data from local storage
localStorage.removeItem("javaScript");

// todo Local Storage can only store strings, so when you want to store a complex data structure like array or an object, you need to convert it into a string using JSON.stringify:

//* JSON.stringify: convert a javascript object into a json string.


//* JSON.stringify: Converts a JavaScript object into a JSON string.
// Useful when you want to send data to a server or store it in a text file, as JSON is a common data interchange format.
// const data = { name: "Akshra", age: 23, city: "pune" };
// const jsonString = JSON.stringify(data);
// console.log(jsonString);
// Output: '{"name":"Akshra","age":23,"city":"pune"}'

//* JSON.parse: Converts a JSON string into a JavaScript object.
// Useful when you receive JSON data from a server or read it from a file, and you want to work with it as a JavaScript object.

const jsonString = '{"name":"Akshra","age":23,"city":"pune"}';
const parsedData = JSON.parse(jsonString);
console.log(parsedData);
// Output: { name: 'Akshra', age: 30, city: 'pune' }