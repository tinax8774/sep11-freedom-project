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

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
