# Tool Learning Log

## Tool: **TypeScript**

## Project: **App to help people choose movies, books**

---

### 10/4/2025:
* Started watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs) for about 10 minutes.

    * Built onto Javascript
    * Javascript gives a lot more flexibility.
    * Type Script helps with checking your Javascript code
    * Helps write code faster
Some challenges was trying to install the tool as it was acting up and still not working so next time will include some code.

For the next learning log I'm gonna be writing the actual code and testing out the tool as I have not figured out how to install the tool yet.

### 11/2/2025:
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

* Started looking at the code and learning it's function a bit

``` js
if ("" == 0) {
  // It is! But why??
}
if (1 < x < 5) {
  // True for *any* value of x!
}
```

* Similar to what were doing in conditionals as `==` means something is the same and when put into the if statement it is basically saying that the x value is greater than 1 but less than 5.

``` js
let a = (4
')' expected.
```
* It helps detect errors in code as in this case was a missing parenthesis.

Some challenges were still trying to figure out how to use this tool and understanding its function.

Next time I'm gonna try and see to what extent can it fix mistakes to.



### 11/10/2025:
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

* Typescript can easily know the types of code and can often autocorrect the code.
``` js
const user = {
  name: "Hayes",
  id: 0,
};
```
Can also use the following code:
``` js
interface User {
  name: string;
  id: number;
}
```
* used to show that name is a string and the id is a number.

Challenges were trying to figure out the code as this is not what we learned in class

Next time I'm gonna continue exploring this website and its function.

### 11/23/2025
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

``` js
interface User {
  name: string;
  id: number;
}

class UserAccount {
  name: string;
  id: number;

  constructor(name: string, id: number) {
    this.name = name;
    this.id = id;
  }
}

const user: User = new UserAccount(" John", 3);
```
* This is similar to the classes used in javascript but for this it is using interface.

Challenges were trying to find time to do this learning log and also the code is getting confusing to some extent.

Next time gonna try and test more things out and find time for tinkering.

### 12/6/2025
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

``` js
type WindowStates = "open" | "closed" | "minimized";
type LockStates = "locked" | "unlocked";
type PositiveOddNumbersUnderTen = 1 | 3 | 5 | 7 | 9;
```
* Is used to set strings and number literals

``` js
function getLength(obj: string | string[]) {
  return obj.length;
```
* Is used to take a string or a array.

Challenges were trying to understand how the code is written as this is kinda different

Next time I'm just gonna continue to tinker

### 12/13/2025
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

``` js
function wrapInArray(obj: string | string[]) {
  if (typeof obj === "string") {
    return [obj];

(parameter) obj: string
  }
  return obj;
}
```

* Things can be returned either from a string or an array.

``` js
type StringArray = Array<string>;
type NumberArray = Array<number>;
type ObjectWithNameArray = Array<{ name: string }>;
```
* Similar to variables arrays can also have different values unless it is set to a certain value.

Challenges was finding time to do this learning log and also processing the code in general

Gonna continue tinkering in the upcoming weeks

### 1/15/2026
* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)

``` js
function wrapInArray(obj: string | string[]) {
  if (typeof obj === "string") {
    return [obj];

(parameter) obj: string
  }
  return obj;
}
```
* It allows for the funciton to return different values depending on the string or the array

``` js
const obj = { width: 10, height: 15 };
// Why is this NaN? Spelling is hard!
const area = obj.width * obj.heigth;
```
* It can also access different properties

Challenges was finding time in a busy week to learn my tool

Next time gonna try to spend more time learning my tool

### 3/7/2026
This week only coding happened:

``` js
interface Point {
  x: number;
  y: number;
}
 
function logPoint(p: Point) {
  console.log(`${p.x}, ${p.y}`);
}
 
// logs "12, 26"
const point = { x: 12, y: 26 };
logPoint(point);
``` 
* This is used when both of the shapes are the same shape so they belong in the same type

``` js
class VirtualPoint {
  x: number;
  y: number;
 
  constructor(x: number, y: number) {
    this.x = x;
    this.y = y;
  }
}
 
const newVPoint = new VirtualPoint(13, 56);
logPoint(newVPoint); // logs "13, 56"
``` 
* Shows that there is no difference between how clases and objects form to make shapes

Challenges was finding time to tinker

Next step is to use the tool to make my MVP for my project

### 3/21/2026
This week was mainly only coding that happened

``` js
const point3 = { x: 12, y: 26, z: 89 };
logPoint(point3); // logs "12, 26"
 
const rect = { x: 33, y: 3, width: 30, height: 80 };
logPoint(rect); // logs "33, 3"
 
const color = { hex: "#187ABF" };
logPoint(color);
Argument of type '{ hex: string; }' is not assignable to parameter of type 'Point'.
  Type '{ hex: string; }' is missing the following properties from type 'Point': x, y
```
* `point` and `Point` are different but `point` is being compared to `Point`

``` js
class VirtualPoint {
  x: number;
  y: number;
 
  constructor(x: number, y: number) {
    this.x = x;
    this.y = y;
  }
}
 
const newVPoint = new VirtualPoint(13, 56);
logPoint(newVPoint); // logs "13, 56"
```
* There is not a difference between classes and objects conform when it comes to shapes

``` js
class Student {
  fullName: string;
  constructor(
    public firstName: string,
    public middleInitial: string,
    public lastName: string
  ) {
    this.fullName = firstName + " " + middleInitial + " " + lastName;
  }
}
 
interface Person {
  firstName: string;
  lastName: string;
}
 
function greeter(person: Person) {
  return "Hello, " + person.firstName + " " + person.lastName;
}
 
let user = new Student("Jane", "M.", "User");
 
document.body.textContent = greeter(user);
```
* `public` has similar functions to `var` which is used to create properties with a certain name. 

Challenges were balancing homework assignments for other classes and tinkering 

Next step is to continue to code my freedom project

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
