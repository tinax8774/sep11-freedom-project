# Entry 2: Tinkering with tool
##### 12/20/2025


### Context
During the past 1 month I have been tinkering with my tool TypeScript and finding ways on how I could incorporate this tool in my freedom project for this year. I realized this tool is very similar to grammarly but instead of normal english text it is used for detecting errors in code. Below is what I have learned from this tool.




* Started watching [this video](https://www.youtube.com/watch?v=d56mG7DezGs) for about 10 minutes.


   * Built onto Javascript
   * Javascript gives a lot more flexibility.
   * Type Script helps with checking your Javascript code
   * Helps write code faster
* Started looking at the code and learning it's function a bit


``` js
if ("" == 0) {
 // It is! But why??
}
if (1 < x < 5) {
 // True for *any* value of x!
}
```


* Similar to what we're doing in conditionals as `==` means something is the same and when put into the if statement it is basically saying that the x value is greater than 1 but less than 5.


``` js
let a = (4
')' expected.
```
* It helps detect errors in code as in this case was a missing parenthesis.


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
* used to show that the name is a string and the id is a number.


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
* This is similar to the classes used in javascript but for this it is using an interface.
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
* Is used to take a string or an array.
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
### Goal for Winter Break:
For winter break my goal is to try and tinker with my tool for at least 1 hour balancing between work for other classes and spending time with family.




### Sources
The sources I used was the [website](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html) and also a youtube [video](https://www.youtube.com/watch?v=d56mG7DezGs)


### EDP(Engineering Design Process)
We are currently on the first step as we are slowly learning our tool and haven't started to do much yet.


### Skills
One skill is time management as I find time in my day in order to tinker with my tool even if I have a lot of other things to do. I find time during my day to learn how this tool works and found it very useful.


Another skill is attention to detail as I looked at every line of code even if the use was not that significant I still found out the use of the code and took my time to figure out how it works.








[Previous](entry01.md) | [Next](entry03.md)


[Home](../README.md)
