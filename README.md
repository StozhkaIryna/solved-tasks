# Solved Tasks 

[Training JS #1: create your first JS function and print "Helloworld!](https://www.codewars.com/kata/571ec274b1c8d4a61c0000c8)
```javascript
function helloWorld (){
var str = 'Hello World!';
console.log(str);
return 'helloWorld';
}
```
[Multiply](https://www.codewars.com/kata/50654ddff44f800200000004)
```javascript
function multiply(a, b){
  return a * b;
}
```
[5 without numbers !!](https://www.codewars.com/kata/50654ddff44f800200000004)
```javascript
function multiply(a, b){
  return a * b;
}
```
[Beginner Series #2 Clock](https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a)
```javascript
function past(h, m, s){
 seconds = 0
    if (h > 0);
      seconds = seconds + h * 3600;
    if (m > 0);
      seconds = seconds + m * 60;
    if (s > 0);
      seconds = seconds + s;
    return seconds * 1000;
 console.log(past(0,1,1))
}
```
[Third Angle of a Triangle](https://www.codewars.com/kata/5a023c426975981341000014)
```javascript
function otherAngle(a, b) {
  return 180 - a - b;
  console.log(otherAngle(30, 60));
  console.log(otherAngle(60, 60));
  console.log(otherAngle(43, 78));
  console.log(otherAngle(10, 20));
}
```
[Sum of angles](https://www.codewars.com/kata/5a03b3f6a1c9040084001765)
```javascript
function angle(n) {
  return  (n - 2) * 180;
  console.log(angle(3));
  console.log(angle(4));
}
```
[For Twins: 2. Math operations](https://www.codewars.com/kata/59c287b16bddd291c700009a)
```javascript
function iceBrickVolume(r, b, rim) {
   const v = 2 * r * r * (b - rim);
  return v;
}
```
[I love you, a little , a lot, passionately ... not at all](https://www.codewars.com/kata/57f24e6a18e9fad8eb000296)
```javascript
function howMuchILoveYou(nbPetals) {
  const phrases = ["I love you", "a little", "a lot", "passionately", "madly", "not at all"];
  const n = nbPetals % 6
   if (n === 0) 
   return phrases[5];
   else 
   return phrases[n - 1];
   }
```
[Breaking chocolate problem](https://www.codewars.com/kata/534ea96ebb17181947000ada)
```javascript
function breakChocolate(n,m) {
    if (m <= 0 || n <= 0) return 0;
    return n * m - 1; 
}
```
[Chuck Norris VII - True or False? (Beginner)](https://www.codewars.com/kata/570669d8cb7293a2d1001473)
```javascript
function ifChuckSaysSo(hoo){
  return (0 < -1|| -1>0 )
}
```
[Super Duper Easy](https://www.codewars.com/kata/55a5bfaa756cfede78000026)
```javascript
function problem(x){
  if (typeof x === 'number')
  return x = x*50+6;
  else 
  return 'Error';
}
```
[Convert boolean values to strings 'Yes' or 'No'.](https://www.codewars.com/kata/53369039d7ab3ac506000467)
```javascript
function boolToWord( bool ){
  return bool ?'Yes':'No'
}
```
[Is n divisible by x and y?](https://www.codewars.com/kata/5545f109004975ea66000086)
```javascript
function isDivisible(n, x, y) {
 return n % x == 0 && n % y === 0;
}
```
[Is this a triangle?](https://www.codewars.com/kata/56606694ec01347ce800001b)
```javascript
function isTriangle(a,b,c) {
  return a < b+c && b < a+c && c < b+a;
}
```
[Power of two](https://www.codewars.com/kata/534d0a229345375d520006a0)
```javascript
function isPowerOfTwo(n){
 if (n === 1) return true;
 while (n > 1) {
 n = n/2
 }
 if (n === 1)
  return true; 
  else
  return false
}
```
[Type of sum](https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba)
```javascript
function typeOfSum(a, b) {
  return typeof(a+b);
}
```
[Beginner Series #3 Sum of Numbers](https://www.codewars.com/kata/55f2b110f61eb01779000053)
```javascript
function getSum( a,b ){
 let  sum = 0;
   if (a<b){
   for (let i = a; i <= b; ++i){
   sum += i;
   }
  } else {
    for (let i = b; i <=a; ++i){
    sum += i;
    }
}
return sum
}
```
[Convert a Number to a String!](https://www.codewars.com/kata/5265326f5fda8eb1160004c8)
```javascript
function numberToString(num) {
  return (num.toString());
  return (num + '');
  return (String(num));
}
```
[Number toString](https://www.codewars.com/kata/number-tostring)
```javascript
var a = 123..toString();
var a = 123 .toString()
var a = (123).toString();
var a = 123 + '';
var a = "123";
var a = Number(123).toString();
var a = 123["toString"]();
let a = `${123}`;
const a = '123';
```
[Convert a String to a Number!](https://www.codewars.com/kata/convert-a-string-to-a-number/javascript)
```javascript
var stringToNumber = function(str){
  return parseInt(str);
  return + "";
  return + str;
  return toNumber(str);
  return +myStringVariable;
}
```
[Convert a Boolean to a String](https://www.codewars.com/kata/convert-a-boolean-to-a-string)
```javascript
function booleanToString(b){
  return b + "";
  return b.toString();
  return b["toString"]();
  return `${b}`;
  return "b";
}
```
[Sum The Strings](https://www.codewars.com/kata/sum-the-strings)
```javascript
function sumStr(a,b) {
  return (+a) + (+b) + '';
 return Number(a) + Number(b) + '';
}
```
[Discover The Original Price](https://www.codewars.com/kata/discover-the-original-price/javascript)
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
 const pers = (100-salePercentage)
  return (discountedPrice/pers*100).toFixed(2);


const discoverOriginalPrice = (dis, sale) => Math.round(dis/(1-(sale/100))*100)/100;
```
[Formatting decimal places #0](https://www.codewars.com/kata/formatting-decimal-places-number-0/javascript)
```javascript
function twoDecimalPlaces(n) {
  return (+n.toFixed(2));
}
```
[How many times should I go?](https://www.codewars.com/kata/how-many-times-should-i-go/javascript)
```javascript
function howManyTimes(annualPrice, individualPrice) {
 return Math.ceil(annualPrice/individualPrice)
}
```
[Count Odd Numbers below n](https://www.codewars.com/kata/count-odd-numbers-below-n/javascript)
```javascript
 function oddCount(n){
 const oddCount = n
 return Math.floor(n/2)
}
```
[Keep Hydrated!](https://www.codewars.com/kata/keep-hydrated-1/javascript)
```javascript
function litres(time) {
  const w = 0.5;
  return Math.floor(time * w);
}
```
[Area of a Square](https://www.codewars.com/kata/area-of-a-square/javascript)
```javascript
function squareArea(A){
  return Number(Math.pow(2 * A / 3.1416, 2).toFixed(2))
}
```
[Return the closest number multiple of 10](https://www.codewars.com/kata/return-the-closest-number-multiple-of-10/javascript)
```javascript
const closestMultiple10 = num => {
  return Math.round(num/10)*10;
};
```
[Keep up the hoop](https://www.codewars.com/kata/keep-up-the-hoop/javascript)
```javascript
 function hoopCount (n) {
   if (n<10) return "Keep at it until you get it";
   if (n>=10) return "Great, now move on to tricks";
}
```
[Simple Comparison?](https://www.codewars.com/kata/simple-comparison/javascript)
```javascript
function add(a, b){
	return (+a) == (+b);
}
```

[Return the closest number multiple of 10](https://www.codewars.com/kata/return-the-closest-number-multiple-of-10/javascript)
```javascript
 const closestMultiple10 = num => {
  return Math.round(num/10)*10;
};
```
[Keep up the hoop](https://www.codewars.com/kata/keep-up-the-hoop/javascript)
```javascript
 function hoopCount (n) {
   if (n<10) return "Keep at it until you get it";
   if (n>=10) return "Great, now move on to tricks";
}
```
[Simple Comparison?](https://www.codewars.com/kata/simple-comparison/javascript)
```javascript
 function add(a, b){
	return (+a) == (+b);
}
```
[Is he gonna survive?](https://www.codewars.com/kata/is-he-gonna-survive/javascript)
```javascript
 function hero(bullets, dragons){
if (bullets >= dragons * 2) return true;
else return false
}
```
[Even or Odd](https://www.codewars.com/kata/even-or-odd/javascript)
```javascript
 function even_or_odd(n) {
  if (n%2) return "Odd";
  else return "Even";
}
```

```javascript
function even_or_odd(number){
  return number % 2 ? "Odd" : "Even"
}
```
```javascript
function even_or_odd(number) {
   return number % 2 === 0 ? 'Even' : 'Odd';
}
```
[Simple multiplication](https://www.codewars.com/kata/simple-multiplication/javascript)
```javascript
 function simpleMultiplication(n) {
    if (n%2 === 0) return n*8;
    if (n%2 === 1) return n*9;
}
```
[What's the real floor?](https://www.codewars.com/kata/whats-the-real-floor/javascript)
```javascript
function getRealFloor(n) {
  if (n > 14) return n - 2
  if (n > 0) return n - 1
  return n
}
```
[Determine offspring sex based on genes XX and XY chromosomes](https://www.codewars.com/kata/determine-offspring-sex-based-on-genes-xx-and-xy-chromosomes/train/javascript)
```javascript
function chromosomeCheck(sperm) {
   if(sperm == "XY" || sperm == "YX" || sperm == "YY"){
   return "Congratulations! You're going to have a son.";
   }else if(sperm == "XX"){
   return "Congratulations! You're going to have a daughter.";
   }
}
```
[Calculate BMI](https://www.codewars.com/kata/calculate-bmi/javascript)
```javascript
function bmi(w, h){
 const b = (w/h/h);
 if (b <= 18.5) return 'Underweight';
 if (b <= 25.0) return 'Normal';
 if (b <= 30.0) return 'Overweight';
 if (b > 30) return 'Obese'
}
```
```javascript
const bmi = (weight, height) => {

 let x = (weight / (height * height))
 
 return x <= 18.5 ? "Underweight"
      : x <= 25.0 ? "Normal"
      : x <= 30.0 ? "Overweight"
      : x > 30   && "Obese"
}
```

[Alan Partridge II - Apple Turnover](https://www.codewars.com/kata/alan-partridge-ii-apple-turnover/train/javascript)
```javascript
function apple(x){
  if (x*x >= 1000) return 'It\'s hotter than the sun!!';
  if (x <= 999) return 'Help yourself to a honeycomb Yorkie for the glovebox.';
} 
```
[Sleigh Authentication](https://www.codewars.com/kata/sleigh-authentication/javascript)
```javascript
function Sleigh() {}
Sleigh.prototype.authenticate = function(name, password) {
return name === 'Santa Claus' && password === 'Ho Ho Ho!';
};
```
[Student's Final Grade](https://www.codewars.com/kata/students-final-grade/javascript)
```javascript
function finalGrade (e, p) {
  if (e > 90 || p > 10) return 100;
  if (e > 75 && p >= 5) return 90;
  if (e > 50 && p >= 2) return 75;
  return 0;
}
```
[Can we divide it?](https://www.codewars.com/kata/can-we-divide-it/javascript)
```javascript
function isDivideBy(n, a, b) {
  if (n%a == 0 && n%b == 0) return true;
  else return false;
}
```
[L1: Set Alarm](https://www.codewars.com/kata/l1-set-alarm/train/javascript)
```javascript
function setAlarm(employed, vacation){
  return employed && !vacation;
}
```
```javascript
function setAlarm(employed, vacation){
return employed === true && vacation === false;
}
```
[Rock Paper Scissors!](https://www.codewars.com/kata/rock-paper-scissors/javascript)
```javascript
const rps = (p1, p2) => {
 if (p1 === 'rock' && p2 === 'scissors') return 'Player 1 won!';
 if (p1 === 'scissors' && p2 === 'paper') return 'Player 1 won!';
 if (p1 === 'paper' && p2 === 'rock') return 'Player 1 won!';
   if (p2 === 'rock' && p1 === 'scissors') return 'Player 2 won!';
   if (p2 === 'scissors' && p1 === 'paper') return 'Player 2 won!';
   if (p2 === 'paper' && p1 === 'rock') return 'Player 2 won!';
      else return 'Draw!';
}
```
[** Calculate Two People's Individual Ages !!](https://www.codewars.com/kata/calculate-two-peoples-individual-ages/javascript)
```javascript
 function getAges(s,d){
 if (d<0||s<0) return null;
   s=s/2
   d/=2
   if (s+d<0||s-d<0) return null;
   return [s+d,s-d]
};
```
[101 Dalmatians - squash the bugs, not the dogs!](https://www.codewars.com/kata/56f6919a6b88de18ff000b36)
```javascript
function howManyDalmatians(n){
  if (n <= 10) return "Hardly any";
  else if (n <= 50) return "More than a handful!";
  else if (n === 101) return "101 DALMATIANS!!!";
  else return "Woah that's a lot of dogs!";
}
```
[Do I get a bonus?](https://www.codewars.com/kata/do-i-get-a-bonus/javascript)
```javascript
function bonusTime(salary, bonus) {
 const s1 = '£'+ salary * 10 + '';
 const s2 = '£'+ salary + '';
 if (salary > 0 && bonus === true)  return s1;
 if (salary > 0 && bonus === false) return s2;
}
```
```javascript
function bonusTime(salary, bonus) {
  return bonus ? `£${10 * salary}` : `£${salary}`;
}
```
[Training JS #7: if..else and ternary operator](https://www.codewars.com/kata/training-js-number-7-if-dot-else-and-ternary-operator/javascript)
```javascript
function saleHotdogs(n){
   if (n<5) return n*100;
   if (n>=5 && n<10) return n*95;
   if (n>=10) return n*90;
 }
```
[Be Concise I - The Ternary Operator](https://www.codewars.com/kata/be-concise-i-the-ternary-operator/javascript)
```javascript
function describeAge(a) {    
  return "You're a(n) " + (
    a > 64 ? "elderly":
      a > 17 ? "adult":
        a > 12 ? "teenager":
          "kid"
    );
```
[Basic Mathematical Operations](https://www.codewars.com/kata/basic-mathematical-operations/javascript)
```javascript
function basicOp(o, v1, v2)
{
  switch(o){
  case'+':return v1+v2;
  case'-':return v1-v2;
  case'*':return v1*v2;
  case'/':return v1/v2;
  }
  return 0;
}
```
[Simple calculator](https://www.codewars.com/kata/simple-calculator/javascript)
```javascript
 function calculator(a,b,s){
  if (a === "number", b === "number", s === "+" ) return (a+b);
   if (a === "number", b === "number", s === "-" ) return (a-b);
    if (a === "number", b === "number", s === "*" ) return (a*b);
    if (a === "number", b === "number", s === "/" ) return (a/b);
      else return "unknown value";
}
```
```javascript
 function calculator(a,b,s){
const arr = ['*', '/', '+', '-'];
  if (arr.includes(s) && Number.isInteger(a) && Number.isInteger(b)){
  return eval(a+s+b)
} else {
 return "unknown value";
 }
 }
```
[Sum of Multiples](https://www.codewars.com/kata/sum-of-multiples/javascript)
```javascript
 function sumMul(n,m){
 if (n >= m) return "INVALID";
  let x = 0;
   for (i = n; i < m; i+=n){
   x += i;
 }
   return x;
}
```
```javascript
function sumMul(n, m) {
    const arr = [];
    for (let i = 0; i < m; i++) {
        if (i % n === 0) {
            arr.push(i);
        }
    }
    const sum = arr.reduce((a, b) => a + b, 0);
    return arr.length < 1 ? `INVALID` : sum;
}
```

[Difference Of Squares](https://www.codewars.com/kata/difference-of-squares/javascript)
```javascript
const differenceOfSquares = n => {
  const nN = Array.from({ length: n }, (_, index) => index + 1)
  const sqSum = nN.reduce((total, number) => total + number, 0) ** 2
  const sumSq = nN.reduce((total, number) => total + number ** 2, 0)
  return sqSum - sumSq
}
```
[Switch it Up!](https://www.codewars.com/kata/switch-it-up/javascript)
```javascript
function switchItUp(number){
 switch (number){
    case 0:
      return 'Zero'
    case 1:
      return 'One'
    case 2:
      return 'Two'
    case 3:
      return 'Three'
    case 4:
      return 'Four'
    case 5:
      return 'Five'
    case 6:
      return 'Six'
    case 7:
      return 'Seven'
    case 8:
      return 'Eight'
    case 9:
      return 'Nine'
  }
}
```
```javascript
var a = number;
var b = {
0: "Zero",
1: "One",
2: "Two",
3: "Three",
4: "Four",
5: "Five",
6: "Six",
7: "Seven",
8: "Eight",
9: "Nine"
};
return b[a];
```
[isReallyNaN](https://www.codewars.com/kata/isreallynan/javascript)
```javascript
const isReallyNaN = (val) => {
  return Number.isNaN(val)
  return true || false;
};
```
[Is integer safe to use?](https://www.codewars.com/kata/is-integer-safe-to-use/javascript)
```javascript
function SafeInteger(n){
  return Number.isSafeInteger(n);
}
```
[Return Negative](https://www.codewars.com/kata/return-negative/javascript)
```javascript
function makeNegative(num) {
 return -Math.abs(num);
}
```
[Sum of the first nth term of Series](https://www.codewars.com/kata/sum-of-the-first-nth-term-of-series/javascript)
```javascript
function SeriesSum(n){
  var a = 0;
  for ( i = 0; i < n; ++i){
   a += 1 / (1 + i * 3)
  }
  return a.toFixed(2)
  return a.prototype.toString(n)
}
```
[Grasshopper - Summation](https://www.codewars.com/kata/grasshopper-summation/javascript)
```javascript
var summation = function (num) {
  let x = 0;
  for (i = 1; i <= num; i++) {
    x += i;
  }
  return x;
}
```
[Draw stairs](https://www.codewars.com/kata/draw-stairs/javascript)
```javascript
function drawStairs(n) {
  result = [];
  for (let i = 0; i < n; i++) {
    space = ' ';
    result.push('I\n' + space.repeat(i));
  }
  result[n - 1] = 'I';
  return result.join(' ');
  return [...Array(n)].map((_, i) => ' '.repeat(i) + 'I').join('\n');
}
```
```javascript
function drawStairs(n) {
let step = "I";
  for(i = 1; i<n; i++){
   step+="\n" + " ".repeat(i) + "I";
  } return step
}
```
