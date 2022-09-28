// This is an in-line comment.

/* This is a
multi-line comment */

---

var ourName;
변수는 숫자, 문자, $, _를 쓸 수 있지만 공백이 있으면 안 되고, 숫자로 시작할 수 없다.

---

var myVar;
myVar = 5;

---

var myVar;
myVar = 5;
var myNum;
myNum = myVar;

---

var myVar = 0;

---

var myName = "your name";

---

// Only change code below this line
var a = 5;
var b = 10;
var c = "I am a";
// Only change code above this line

a = a + 1;
b = b + 5;
c = c + " String!";

---

var camper = "James";
var camper = "David";
console.log(camper);

let camper = "James";
let camper = "David";

---

const FAV_PET = "Cats";
FAV_PET = "Dogs";

---

const FCC = "freeCodeCamp"; // Change this line
let fact = "is cool!"; // Change this line
fact = "is awesome!";
console.log(FCC, fact); // Change this line

---

const myVar = 5 + 10;

---

const myVar = 12 - 6;

---

const myVar = 13 * 13;

---

const myVar = 16 / 2;

---

i++;
i = i + 1;

---

i--;
i = i - 1;

---

const ourDecimal = 5.7;

// Only change code below this line

---

const product = 2.0 * 2.5;

---

const quotient = 4.4 / 2.0; // Change this line

---

const remainder = 11 % 3;

---

let a = 3;
let b = 17;
let c = 12;

// Only change code below this line
a += 12;
b += 9;
c += 7;

---

let a = 11;
let b = 9;
let c = 3;

// Only change code below this line
a -= 6;
b -= 15;
c -= 1;

---

let a = 5;
let b = 12;
let c = 4.6;

// Only change code below this line
a *= 5;
b *= 3;
c *= 10;

---

let a = 48;
let b = 108;
let c = 33;

// Only change code below this line
a /= 12;
b /= 4;
c /= 11;

---

const myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line

---

const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';

---

const myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; // Change this line

FirstLine
    \SecondLine
ThirdLine

---

const myStr = "This is the start. " + "This is the end."; // Change this line

---

let myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";

---

// Only change code below this line
const myName = "freeCodeCamp";
const myStr = "My name is " + myName + "and I am well!";

---

const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

---

// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length;

---

// Setup
let firstLetterOfLastName = "L";
const lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line

---

// not change
let myStr = "Bob";
myStr[0] = "J";

// change
let myStr = "Bob";
myStr = "Job";

---

// Setup
const lastName = "Lovelace";

// Only change code below this line
const thirdLetterOfLastName = lastName[2]; // Change this line

---

// Setup
const lastName = "Lovelace";

// Only change code below this line
const lastLetterOfLastName = lastName[lastName.length - 1]; // Change this line

---

// Setup
const lastName = "Lovelace";

// Only change code below this line
const secondToLastLetterOfLastName = lastName[lastName.length - 2]; // Change this line

---

const sentence = "It was really " + "hot" + ", and we " + "laughed" + " ourselves " + "silly" + ".";

---

// Only change code below this line
const myArray = ["num", 1];

---

const teams = [["Bulls", 23], ["White Sox", 45]];

---

const myArray = [50, 60, 70];
var myData = myArray[0];

---

// Setup
const myArray = [18, 64, 99];
myArray[0] = 45
// Only change code below this line

---

const arr = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];

const subarray = arr[3];
const nestedSubarray = arr[3][0];
const element = arr[3][0][1];

---

// Setup
const myArray = [["John", 23], ["cat", 2]];
myArray.push(["dog", 3]);
// Only change code below this line

---

const threeArr = [1, 4, 6];
const oneDown = threeArr.pop(); // 6
console.log(oneDown);
console.log(threeArr);

---

const ourArray = ["Stimpson", "J", ["cat"]];
const removedFromOurArray = ourArray.shift(); // Stimpson

---

const ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ["J", "cat"]
ourArray.unshift("Happy"); // ["Happy", "J", "cat"];

---