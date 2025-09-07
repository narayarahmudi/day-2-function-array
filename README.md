# day-2-function-array
This repository contains my Day 2 progress in learning JavaScript fundamentals, focusing on functions and arrays. Three practical exercises demonstrate core programming concepts including conditional logic, array manipulation, and function implementation.


## NOTES
```javascript
// PROBLEM 1
let numbers = [10, 20, 30, 50, 65];
function above30(n) {
    if (n > 30) {
        return n + ' Greater than 30';
    } else if (n === 30) {
        return n + ' Equal to 30';
    } else {
        return n + ' Below 30';
    }
}
console.log(above30(numbers[0]));
console.log(above30(numbers[1]));
console.log(above30(numbers[2]));
console.log(above30(numbers[3]));
console.log(above30(numbers[4]));
// PROBLEM 2
let colors = ["Red", "Blue", "Green", "Yellow"];
if (colors[1] == 'Blue') {
    console.log('Correct! The color is blue.');
} else {
    console.log('Wrong!');
}
// PROBLEM 3
let scores = [85, 92, 58, 70, 100];
let convertScore = (score) => {
    if (score >= 90) {
        return 'Grade A';
    } else if (score >= 80) {
        return 'Grade B';
    } else if (score >= 70) {
        return 'Grade C';
    } else {
        return 'Grade D';
    }
}
console.log(scores[0], '->', convertScore(scores[0]));
console.log(scores[1], '->', convertScore(scores[1]));
console.log(scores[2], '->', convertScore(scores[2]));
console.log(scores[3], '->', convertScore(scores[3]));
console.log(scores[4], '->', convertScore(scores[4]));
```

