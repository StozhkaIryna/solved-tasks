# Solved Tasks 

###Training JS #1: create your first JS function and print "Helloworld!"
* https://www.codewars.com/kata/571ec274b1c8d4a61c0000c8
```javascript
function helloWorld (){
var str = 'Hello World!';
console.log(str);
return 'helloWorld';
}
```
### Multiply
* https://www.codewars.com/kata/50654ddff44f800200000004
```javascript
function multiply(a, b){
  return a * b;
}
```
### 5 without numbers !!
*https://www.codewars.com/kata/50654ddff44f800200000004
```javascript
function multiply(a, b){
  return a * b;
}
```
### Beginner Series #2 Clock
* https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a
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
### Third Angle of a Triangle
* https://www.codewars.com/kata/5a023c426975981341000014
```javascript
function otherAngle(a, b) {
  return 180 - a - b;
  console.log(otherAngle(30, 60));
  console.log(otherAngle(60, 60));
  console.log(otherAngle(43, 78));
  console.log(otherAngle(10, 20));
}
```
### Sum of angles
* https://www.codewars.com/kata/5a03b3f6a1c9040084001765
```javascript
function angle(n) {
  return  (n - 2) * 180;
  console.log(angle(3));
  console.log(angle(4));
}
```
### For Twins: 2. Math operations
* https://www.codewars.com/kata/59c287b16bddd291c700009a
```javascript
function iceBrickVolume(r, b, rim) {
   const v = 2 * r * r * (b - rim);
  return v;
}
```
### I love you, a little , a lot, passionately ... not at all
* https://www.codewars.com/kata/57f24e6a18e9fad8eb000296
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
### Breaking chocolate problem
* https://www.codewars.com/kata/534ea96ebb17181947000ada
```javascript
function breakChocolate(n,m) {
    if (m <= 0 || n <= 0) return 0;
    return n * m - 1; 
}
```
### Chuck Norris VII - True or False? (Beginner)
* https://www.codewars.com/kata/570669d8cb7293a2d1001473
```javascript
function ifChuckSaysSo(hoo){
  return (0 < -1|| -1>0 )
}
```
### Super Duper Easy
* https://www.codewars.com/kata/55a5bfaa756cfede78000026
```javascript
function problem(x){
  if (typeof x === 'number')
  return x = x*50+6;
  else 
  return 'Error';
}
```
### Convert boolean values to strings 'Yes' or 'No'.
* https://www.codewars.com/kata/53369039d7ab3ac506000467
```javascript
function boolToWord( bool ){
  return bool ?'Yes':'No'
}
```
### Is n divisible by x and y?
* https://www.codewars.com/kata/5545f109004975ea66000086
```javascript
function isDivisible(n, x, y) {
 return n % x == 0 && n % y === 0;
}
```
### Is this a triangle?
* https://www.codewars.com/kata/56606694ec01347ce800001b
```javascript
function isTriangle(a,b,c) {
  return a < b+c && b < a+c && c < b+a;
}
```
### Power of two
* https://www.codewars.com/kata/534d0a229345375d520006a0
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
### Type of sum
* https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba
```javascript
function typeOfSum(a, b) {
  return typeof(a+b);
}
```
### Beginner Series #3 Sum of Numbers
* https://www.codewars.com/kata/55f2b110f61eb01779000053
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
### Convert a Number to a String!
* https://www.codewars.com/kata/5265326f5fda8eb1160004c8
```javascript
function numberToString(num) {
  return (num.toString());
  return (num + '');
  return (String(num));
}
```
### Number toString
* https://www.codewars.com/kata/number-tostring
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
### Convert a String to a Number!
* https://www.codewars.com/kata/convert-a-string-to-a-number/javascript
```javascript
var stringToNumber = function(str){
  return parseInt(str);
  return + "";
  return + str;
  return toNumber(str);
  return +myStringVariable;
}
```
### Convert a Boolean to a String
* https://www.codewars.com/kata/convert-a-boolean-to-a-string
```javascript
function booleanToString(b){
  return b + "";
  return b.toString();
  return b["toString"]();
  return `${b}`;
  return "b";
}
```
### Sum The Strings
* https://www.codewars.com/kata/sum-the-strings
```javascript
function sumStr(a,b) {
  return (+a) + (+b) + '';
 return Number(a) + Number(b) + '';
}
```
### Discover The Original Price
* https://www.codewars.com/kata/discover-the-original-price/javascript
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
 const pers = (100-salePercentage)
  return (discountedPrice/pers*100).toFixed(2);


const discoverOriginalPrice = (dis, sale) => Math.round(dis/(1-(sale/100))*100)/100;
```
### Formatting decimal places #0
* https://www.codewars.com/kata/formatting-decimal-places-number-0/javascript
```javascript
function twoDecimalPlaces(n) {
  return (+n.toFixed(2));
}
```
### How many times should I go?
* https://www.codewars.com/kata/how-many-times-should-i-go/javascript
```javascript
function howManyTimes(annualPrice, individualPrice) {
 return Math.ceil(annualPrice/individualPrice)
}
```
