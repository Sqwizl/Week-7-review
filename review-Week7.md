Stacey Eldershaw

Question 1

let name = "Stacey Eldershaw";

Question 2

let age = 30;

Question 3

let isStudent = true;

Question 4

const hikingTime = 4.5;
const keaBirdsSpotted = 2;

if (hikingTime <6 === keaBirdsSpotted >3); {
  console.log("Great progress on the Milford Track")
}

Question 5

let temperature = 25;

if (temperature > 20) {
  console.log("its warm");
}

Question 6

let score  = 95;

if (score >= 90){
  console.log("Excellent!");
}
else if (score >= 70 === 90){
  console.log("Good job!");
}
else {
  console.log("Keep Trying");
}

Question 7

let password = 'password';
let correctPassword= 'secret123';

if (password === correctPassword) {
    console.log('Access Granted');
}
else {
    console.log('Access Denied');
    }

Question 9

let dayOfWeek = "Friday";

if (dayOfWeek === "Friday") {
    console.log("TGIF");
}

Question 10

const temperature = 18;
const isRaining = true;
const windSpeed = 12;
const hasUmbrella = false;

if ((temperature > 20 && isRaining === false) || (windSpeed < 20 && hasUmbrella)) {
    console.log("Perfect day for a beach walk then hop on the Boblo ");
} else {
    console.log("Better stay indoors today! ");
}

What will be logged?

"Better stay indoors today!"
the values given for the variable will create false boolean values as 18 is not greater than 20.
isRaining will return false as the const is true. which therefore will create a false value for the first IF variable.
windSpeed is true but the next variable hasUmbrella is false.
The whole condtion would render false || false, which therefore would be false.
Therefore the only block that will run and bee logged is the last bloack of "Better stay indoors today!"

Question 8

let name = "Stacey";

function greet(name) {
  return "Hello " + name ;
}

console.log(greet("Stacey"));