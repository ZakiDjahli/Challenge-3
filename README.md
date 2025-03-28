
// challenge java script 3

let a = 1_08;
let b = 2_08.5
let c = 1e2;
let d = 2.4;



// Find Smallest Number in All Variables and Return Integer
console.log(Math.min(a, b , c , d,Number.parseInt(d)));
// qustion Done

// Use Variable a + d One Time To get the needed Output

console.log((a + d) * 100 - 1040) //10000

// qustion Done



// get integer "2" From d variable With 4 Methods
console.log(Math.floor(d));
console.log(Number.parseInt(2.4));
console.log(Math.trunc(d));
console.log(Number(Number.parseInt(d)));

// qustion Done


// Use Variables b + d To Get This Values

console.log((d * b / 10 + 16.63).toString()); // 66.67 = String
console.log(Math.floor(d * b / 10 + 17)); // 67 = Number

// qustion Done
