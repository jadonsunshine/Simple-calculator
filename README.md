# Simple-calculator
A simple calculator to test how far i've gotten in javascript and if i can start solving some real life problem
console.log(1);
console.log(6);

let firstName = "Jadon";

let lastName = "kaycee";

let fullName = firstName + " " + lastName;
let title = " Tech and Jadon"

let likes = 10755

let difference = fullName.length - lastName.length;
console.log(difference);

let result = fullName.toUpperCase()
   console.log(result)
let email = "danielkingsley715@gmail.com"

let sliceResult = email.slice(6,14);
console.log(sliceResult);

// so to get a substring from a particular string without using slice
let subStrResult = email.substr(6,8);
console.log(subStrResult);

let subStringResult = email.substring(6,14);
console.log(subStringResult);

fullName.replace("o", " e");

console.log(fullName.replace("o", "e"));

// template strings

let sentence = `This blogpost called ${title} by ${firstName}  has ${likes} likes`
let normalSentence = "This blogpost called" + " " + title + " by " + firstName + " " + "has" + " " +likes  + " likes"

console.log(normalSentence)
console.log(sentence)

// creating html template strings 

let html = `
    <h1>${title}</h1>
    <p> by ${firstName}</p>
    <span> has ${likes} likes</span>
`
console.log(html)
