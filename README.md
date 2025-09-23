// Test Data 1 with disguised variable names
const a1 = 78, b1 = 1.69;
const a2 = 92, b2 = 1.95;

const x = a1 / (b1 ** 2);
const y = a2 / (b2 ** 2);

const result = x > y;

console.log("Mark's BMI:", x.toFixed(2));
console.log("John's BMI:", y.toFixed(2));
console.log("Mark has higher BMI?", result);
// Test Data 2 with disguised variable names
const a1 = 95, b1 = 1.88;
const a2 = 85, b2 = 1.76;

const x = a1 / (b1 ** 2);
const y = a2 / (b2 ** 2);

const result = x > y;

console.log("Mark's BMI:", x.toFixed(2));
console.log("John's BMI:", y.toFixed(2));
console.log("Mark has higher BMI?", result);
