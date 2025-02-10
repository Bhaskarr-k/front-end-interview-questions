# what is java script?
- java script is a high level and iterpreted programing lanaguage use to create interactive and dynamic web content.
- it is a versalite , lightweight, and event driven language that can run on both the clinet and server sides

# what are the data types supported by java script?
- javascript supports the following data types
- **primitive data types**
- **non primitive data types**
## primitive data types:
- primitive data types are divided into five types they are given below.
### string:
- a string in javascript is a seires of charecters that are surronded by quotes.
- single and doulbe quotes are use for single line statements and thrible quites are used for multiline statements.
### boolean:
- the boolean types has only two values that is **true** and **false**
### undefined:
- a variable that has been declzred but not initiliazed with a value is automatically assigne dthe **undefined** value. 
- it makes the variable exists, but it has no value assigned to it.
### null:
- the special **null value** does not belong to any of the default data types. it forms a seperate types of its own which contains only the null value.
### number:
- the number data type in javascript includes both integers and floating point numbers.
- special values like infinity and infinity values and computational erros, respectively.
## non primitive data types:
- non primitive data types are also known as **reference** data types.
- it is divide dinto three types they are given below
### object:
- javascript objects are key value pairs use to store data created with { } or the new keyword.
- they are fundamental as nearly everything in javascript is an object
- **example**:
let gfg = {

    type: "Company",

    location: "Noida"

}

console.log(gfg.type)
### Arrays:
- an array is a special kind of object used to store an ordered collection of values, which can be of any data type
- any data type means **Homogeneous** and **Hetrogeneous** 
- Homogeneous means the same type. Heterogeneous means diverse(multiple) types.
let a1 = [1, 2, 3, 4, 5];

console.log(a);

let a2 = [1, "two", { name: "Object" }, [3, 4, 5]];

console.log(a2);
### function:
- A function in JavaScript is a block of reusable code designed to perform a specific task when called.

function greet(name) { return "Hello, " + name + "!"; }


console.log(greet("Alice"));

### date object:
- The Date object in JavaScript is used to work with dates and times, allowing for date creation, manipulation, and formatting.

let currentDate = new Date();


console.log(currentDate);

# what is the diffrence between let and const and var?
### var: 
- function scoped allows redclaration and hoiseted with undefined.
### let:
- block scoped and no declaration and hoisetd but not initialized.
### const:
- block scoped and no redeclaraiton and must be initialized during declaration

# exokain how == and === differ?
- ==checks for value **equality with type** coercion.
- === checks for **strict equality without type** coercion.
# what is closure?
- a **closure** is a function that retains access to its outer scope variables evne after the outer function has esecuted.
- **example**:

function outer() {

    let count =0;

    return function inner() {

        count ++

        return count;
    };
}

const counter = outer();

console.log(counter());

console.log(counter());
# what is hoisting?
- **hoisting** is javascript behavior of moving variable and function declarrations to the top of their scope during compailation.

console.log(5);

var a=5;
# explain the concept of this  in javascript?
- **this** refers to the context in which a function is executed its value depends on how the function is called.

const obj = {

    name: "bhasu",

    greet() {

        console.log(this.name);
    },
};

obj.greet();
# what are the javascript prototypes?
- **prototypes** allow object to inherit properties and methods from other objects.

function person(name) {

    this.name = name;

}

person.prototype.greet = function () {

    return `hello, ${this.name}`;

};

const person = new person("siva");

console.log(person.greet());

# what is the diffrence between null and undefined?
- **null**: A deleverate non-value
- **undefined**: A variable decalred but not assigned a value

let x = null;

let y;

console.log(x);  //null

console.log(y);   //undefined
# how does javascript handle asynchronous operations?
- javascript uses the event loop with **callbacks** and **promises** and **async/await for asynchronous operations**
### using call back:

function fetcData(callback) {

    setTimeout(() => {

        callback("data feteched");

    },2000);

}

fetchdata((data) => {

    console.log(data);  // logs data feteched after two seconds

});
### using promise:
function fetechData() {

    return new promise((resolve) = > {

        settimeout (() => {

            resolve("data feteched");

        }, 2000);

    });

}

fetechData(). then((data) => {

    console.log(data);  //logs "data executed" after 2 seconds

})
### using async and await:

function fetchData() {

    return new promise((resolve) => {

        setTimeout(() => {

            resolve("data feteched");

        },2000);

    });

}

async function getData() {

    const data = await fetechData();

    console.log(data);      //logs data after 2 seconds

}

getData();
# what is promise?
- A promise represents the eventual compeltion or failure of an asynchronous operation.

const promise = new promise((resolve, reject) => {

    setTimeout(() => resolve("success"), 1000);

});

promise.then(console.log);   //sucess
# what are async and await functions?
- **async/await** allows writing asynchronous code that looks synchronous.

async function fetchData() {

    const data = await fetch("https://api.example.com);

}

# explain event delegation in javascript?
- **event delegation** allow you to handle events for multiple child elements at the parent level

document.getElementByid("parent).addEventListener("click", (e) => {

    if (e.target.tagname === "BUTTON") {

        console.log("button clicked");

    }
});
# what are javascript modules?
- modules allow you to organize cod einto reusable files using **import and export**

export const greet = () => "hello world";

import { greet } from "./module.js";

console.log(greet());
# how can you prevent a function fom being called multiple times?
- you can use a debunce function

function debounce(func, delay) {

    let timeout;

    return (..args) => {

        clearTimeout(timeout);

        timeout = settimeout(() => func(...args), delay);
    };

}
# what is the event loop?
- the event loop process tasks from the queue stack for asynchronous operations.

console.log("start");

setTimeout(() => console.log("timeout"), 0);

console.log("end");

# what is the diffrence between apply() and call() methods?
### call:
- invokes a funtion with a specific this value and arguments passed individually.
### apply():
- similar to call() but arguments are passed as an array.

function greet(greeting, punctuation) {

    return `{greeting}, ${this.name}${punctuation}`;

}

const person = { name: "basu"};

console.log(greet.call(person,"hello","!"));  //hello siva

console.log(greet.apply("hi","."));  hi siva

# what is bind() method used for?
- the bind() method creates a new function with a specific this value and optional arguments

const obj = {name: "siva"};

function.greet(greeting) {

    return `${greeting},${this.name}`;

}

const bounceGreet = greet.bind(obj);

console.log(bounceGreet("hello"));
# what is javascript event loop?
- the event loop consinuously checks the call stacck and the task queue , exectuing tasks from the queue when the stack is wmpty.

console.log("start");

setTimeout(() => {

    console.log("timeout callback");

},1000);

console.log("end");
# explain the concept of event buikding and event capturing?
### event building:  
- events propagate from the target element to the parent elements.
### event capturing:
- events propagate from the parent elements tot he target element.

document.getElementByid("child").addEventListener("click" () =>

console.log("child"), true);

document.getElementByid("parent").addEventListener("click", () =>

console.log("parent"));
# what is diffrence between shallow copy and deep copy?
- **shallow copy**: copies tonly the first layer of an object
- **deep copy**: copies all layesrs of an object

let obj = {a: 1, b: {c: 2}};

let shallow {..obj};

let deep = JSON.parse(JSON.stringify(obj));
# what are generator funtions?
- generators are special functions that pause execution and resume later

function generator() {

    yield1;

    yield2;

    yield3;

}

const gen = generator();

console.log(gen.next().value);

console.log(gen.next().value);
# what is the new keyword used for?
- the new keyword creates an instance of an oobjet from a constructor function.

function person(name) {

    this.name = name;

}

const person = new Person("siva");

console.log(person.name);
