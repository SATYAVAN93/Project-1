# Project-1
This is my frist repository
// Write a JavaScript program to find the area of a triangle where three sides are 5, 6, 7.
let side1 = 5;
let side2 = 6;
let side3 = 7;

let s = (side1 + side2 + side3)/2;
let area = Math.sqrt(s * ((s - side1) * (s - side2) * (s - side3)));

console.log(area);

// Declare constants for the lengths of the three sides of a triangle
const side4 = 5;
const side5 = 6;
const side7 = 7;

const perimeter = (side4 + side5 + side7) / 2;
const area1  =  Math.sqrt(perimeter *((perimeter - side4) * (perimeter -side5) * (perimeter - side7)));
console.log(area1);

