# Entry 3: Tinkering with Tool
##### 2/2/2026

### Context
Since the last blog entry we have continued to learn our tool during winter break and also in general. During winter break I finished most of the video and continued to learn more concepts that had to do with my tool. Below is some of the things I learned from my tool and most recent learning log.

``` js
type WindowStates = "open" | "closed" | "minimized";
type LockStates = "locked" | "unlocked";
type PositiveOddNumbersUnderTen = 1 | 3 | 5 | 7 | 9;
```
* Used to restrict a variable or function to a certain list

Type	Predicate
string	typeof s === "string"
number	typeof n === "number"
boolean	typeof b === "boolean"
undefined	typeof undefined === "undefined"
function	typeof f === "function"
array	Array.isArray(a)

* Ways to hlep remember what javascript fuction is what

``` js
function wrapInArray(obj: string | string[]) {
  if (typeof obj === "string") {
    return [obj];

(parameter) obj: string
  }
  return obj;
}
```
* Functions can be used used to return different values depending on what is in the array or the function.

* Continued watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs)
``` js
const obj = { width: 10, height: 15 };
// Why is this NaN? Spelling is hard!
const area = obj.width * obj.heigth;
```
* It can also access different properties

``` js
interface Backpack<Type> {
  add: (obj: Type) => void;
  get: () => Type;
}

// This line is a shortcut to tell TypeScript there is a
// constant called `backpack`, and to not worry about where it came from.
declare const backpack: Backpack<string>;

// object is a string, because we declared it above as the variable part of Backpack.
const object = backpack.get();

// Since the backpack variable is a string, you can't pass a number to the add function.
backpack.add(23);
Argument of type 'number' is not assignable to parameter of type 'string'.
```
* This is using arrays but a generic version which sets the value of the array to certain values.

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
* This is used if a shape has the same shape as it shows that they are the same type.

### Sources
The sources I used was the [website](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html) and also a youtube [video](https://www.youtube.com/watch?v=d56mG7DezGs)

### EDP(Engineering Design Process)
We are currently on the fifth step as we are learning our tool and will use this tool later on to make our final project. Our next step is to plan out how we are going to make our project and also continue to learn our tool 

### Goal for upcoming weeks:
My goal for continue to learn my tool is to continue to test out more code on my tool website and find a different video on Youtube that can help me better understand my tool.

### Skills
One skill is time management becasue it takes a lot of time to learn a tool and trying to balance it with all my other classes was definitely a challenge but I found time within my week to sit down and learn my tool for a bit of time everyday.

Another skill is attention to details becasue I often make mistakes while typing code or just anything in general but recently I been able to type code without making as much mistakes as I use to .



Text

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
