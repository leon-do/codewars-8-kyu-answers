# codewars-8-kyu-answers


// 318 answers for codewars

   {
      "_id": "ObjectId(\"58c0bc2444255c74a39d81d1\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc2b44255c74a39d81d2\")",
      "url": "https://www.codewars.com/kata/n-th-power/javascript",
      "title": "N-th Power",
      "answer": "def index(array, n):    try:        return array[n]**n    except:        return -1",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc3044255c74a39d81d3\")",
      "url": "https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/javascript",
      "title": "Convert boolean values to strings 'Yes' or 'No'.",
      "answer": "function boolToWord( bool ){  return bool ? 'Yes':'No';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc3644255c74a39d81d4\")",
      "url": "https://www.codewars.com/kata/to-square-root-or-not-to-square-root/javascript",
      "title": "To square(root) or not to square(root)",
      "answer": "const squareOrSquareRoot = array =>; array.map(a =>; Math.sqrt(a) % 1 == 0 ? Math.sqrt(a) : (a * a));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc3c44255c74a39d81d5\")",
      "url": "https://www.codewars.com/kata/even-or-odd/javascript",
      "title": "Even or Odd",
      "answer": "function even_or_odd(number) {  return number % 2 ? \"Odd\" : \"Even\"}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc4144255c74a39d81d6\")",
      "url": "https://www.codewars.com/kata/simple-fun-number-163-fantastic-person/javascript",
      "title": "Simple Fun #163: Fantastic Person",
      "answer": "const fantasticPerson = t =>; t.findIndex(r =>; r.every(Boolean));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc4644255c74a39d81d7\")",
      "url": "https://www.codewars.com/kata/push-a-hash-slash-an-object-into-array/javascript",
      "title": "Push a hash/an object into array",
      "answer": "var items = [];items.push({a: \"b\", c: \"d\"});",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc4c44255c74a39d81d8\")",
      "url": "https://www.codewars.com/kata/get-character-from-ascii-value/javascript",
      "title": "get character from ASCII Value",
      "answer": "const getChar = String.fromCharCode;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc5244255c74a39d81d9\")",
      "url": "https://www.codewars.com/kata/remove-string-spaces/javascript",
      "title": "Remove String Spaces",
      "answer": "function noSpace(x){  return x.replace(/\\s/g, '');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc5944255c74a39d81da\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc6144255c74a39d81db\")",
      "url": "https://www.codewars.com/kata/multiply/javascript",
      "title": "Multiply",
      "answer": "multiply = function (a, b) {  return a * b;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc6844255c74a39d81dc\")",
      "url": "https://www.codewars.com/kata/sum-without-highest-and-lowest-number/javascript",
      "title": "Sum without highest and lowest number",
      "answer": "function sumArray(array) {  if (array == null) {    return 0;  } else if (array.length < 2) {    return 0;  } else {    array = array.sort(function(a,b) {return a - b;});    var total = 0;    for (var i = 1; i < array.length - 1; i++) {      total += array[i];    }    return total;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc6d44255c74a39d81dd\")",
      "url": "https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/javascript",
      "title": "Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string",
      "answer": "const remove = s =>; s.replace(/!+/g, \"\")+\"!\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc7344255c74a39d81de\")",
      "url": "https://www.codewars.com/kata/invert-values/javascript",
      "title": "Invert values",
      "answer": "function invert(array) {   return array.map( x =>; x === 0 ? x : -x);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc7944255c74a39d81df\")",
      "url": "https://www.codewars.com/kata/calculate-average/javascript",
      "title": "Calculate average ",
      "answer": "function find_average(array) {  var sum = array.reduce((a, b) =>; a + b, 0);  return sum/array.length;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc7e44255c74a39d81e0\")",
      "url": "https://www.codewars.com/kata/regexp-basics-is-it-a-digit/javascript",
      "title": "Regexp Basics - is it a digit?",
      "answer": "String.prototype.digit = function() {  return /^\\d$/.test(this);};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc8444255c74a39d81e1\")",
      "url": "https://www.codewars.com/kata/count-of-positives-slash-sum-of-negatives/javascript",
      "title": "Count of positives / sum of negatives",
      "answer": "function countPositivesSumNegatives(input) {    if (input == null || input.length == 0)      return [];        var positive = 0;    var negative = 0;        for (var i=0, l=input.length; i<l; ++i)    {      if (input[i] >; 0)        ++ positive;      else        negative += input[i];    }        return [positive, negative];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc8e44255c74a39d81e2\")",
      "url": "https://www.codewars.com/kata/how-many-stairs-will-suzuki-climb-in-20-years/javascript",
      "title": "How many stairs will Suzuki climb in 20 years?",
      "answer": "// A proper solutionfunction stairsIn20(a) {  return 20 * a.reduce((s, a) =>; s + a.reduce((s, n) =>; s + n, 0), 0);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc9244255c74a39d81e3\")",
      "url": "https://www.codewars.com/kata/reverse-list-recursively/javascript",
      "title": "Reverse list recursively",
      "answer": "module ReverseRecursively whererevR :: [Int] ->; [Int]revR [] = []revR (x:xs) = revR xs ++ [x]",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc9844255c74a39d81e4\")",
      "url": "https://www.codewars.com/kata/is-it-a-palindrome/javascript",
      "title": "Is it a palindrome?",
      "answer": "module Palindroms whereimport Data.Char (toLower)isPalindrom :: String ->; BoolisPalindrom = (reverse >;>;= (==)) . map toLower",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bc9e44255c74a39d81e5\")",
      "url": "https://www.codewars.com/kata/makeuppercase/javascript",
      "title": "MakeUpperCase",
      "answer": "module MakeUpper whereimport Data.Char (toUpper)makeUpperCase :: String ->; StringmakeUpperCase = map toUpper",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bca444255c74a39d81e6\")",
      "url": "https://www.codewars.com/kata/reversing-words-in-a-string/javascript",
      "title": "Reversing Words in a String",
      "answer": "function reverse(string){  return string.split(' ').reverse().join(' ');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcaa44255c74a39d81e7\")",
      "url": "https://www.codewars.com/kata/pre-fizzbuzz-workout-number-1/javascript",
      "title": "Pre-FizzBuzz Workout #1",
      "answer": "function preFizz(n) {  var output = [];  for (var i=1; i<=n; i++)  {    output.push(i);  }  return output;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcb044255c74a39d81e8\")",
      "url": "https://www.codewars.com/kata/keep-up-the-hoop/javascript",
      "title": "Keep up the hoop",
      "answer": "function hoopCount (n) {  return (n < 10) ? 'Keep at it until you get it' : 'Great, now move on to tricks';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcb544255c74a39d81e9\")",
      "url": "https://www.codewars.com/kata/nba-full-48-minutes-average/javascript",
      "title": "NBA full 48 minutes average",
      "answer": "def nba_extrap(ppg, mpg):    return round(48.0 / mpg * ppg, 1) if mpg >; 0 else 0",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcba44255c74a39d81ea\")",
      "url": "https://www.codewars.com/kata/basic-mathematical-operations/javascript",
      "title": "Basic Mathematical Operations",
      "answer": "function basicOp(operation, value1, value2) {    switch (operation) {        case '+':            return value1 + value2;        case '-':            return value1 - value2;        case '*':            return value1 * value2;        case '/':            return value1 / value2;        default:            return 0;    }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcc044255c74a39d81eb\")",
      "url": "https://www.codewars.com/kata/fake-binary/javascript",
      "title": "Fake Binary",
      "answer": "function fakeBin(x) {    return x.split('').map(n =>; n < 5 ? 0 : 1).join('');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcc744255c74a39d81ec\")",
      "url": "https://www.codewars.com/kata/holiday-viii-duty-free/javascript",
      "title": "Holiday VIII - Duty Free",
      "answer": "function dutyFree(normPrice, discount, hol){  return(Math.floor(hol / normPrice / discount * 100))}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bccd44255c74a39d81ed\")",
      "url": "https://www.codewars.com/kata/filtering-even-numbers-bug-fixes/javascript",
      "title": "Filtering even numbers (Bug Fixes)",
      "answer": "using System;using System.Collections.Generic;using System.Linq;public class Kata{  public static List<int>; FilterOddNumber(List<int>; numbers)  {    return numbers.Where(n =>; n % 2 == 1).ToList();  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcd344255c74a39d81ee\")",
      "url": "https://www.codewars.com/kata/i-love-you-a-little-a-lot-passionately-dot-dot-dot-not-at-all/javascript",
      "title": "I love you, a little , a lot, passionately ... not at all",
      "answer": "const phrases = [    'I love you',    'a little',    'a lot',    'passionately',    'madly',    'not at all',]function howMuchILoveYou(n) {     return phrases[(n - 1) % phrases.length] }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcd944255c74a39d81ef\")",
      "url": "https://www.codewars.com/kata/they-say-that-only-the-name-is-long-enough-to-attract-attention-they-also-said-that-only-a-simple-kata-will-have-someone-to-solve-it-this-is-a-sadly-story-number-1-are-they-opposite/javascript",
      "title": "They say that only the name is long enough to attract attention. They also said that only a simple Kata will have someone to solve it. This is a sadly story #1: Are they opposite?",
      "answer": "function isOpposite(s1,s2){  if(s1 === s2 || s1.toLowerCase() !== s2.toLowerCase()) return false;    for(var i = 0; i < s1.length; i++) {    if(s1.charAt(i) === s2.charAt(i)) return false;  }    return true;  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcde44255c74a39d81f0\")",
      "url": "https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/javascript",
      "title": "Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string",
      "answer": "const remove = s =>; s.replace(/!+/g, \"\")+\"!\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bce744255c74a39d81f1\")",
      "url": "https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/javascript",
      "title": "Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string",
      "answer": "const remove = s =>; s.replace(/!+/g, \"\")+\"!\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bced44255c74a39d81f2\")",
      "url": "https://www.codewars.com/kata/sql-grasshopper-select-columns/javascript",
      "title": "SQL Grasshopper: Select Columns",
      "answer": "SELECT custid, custname, custstate FROM customers;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcf344255c74a39d81f3\")",
      "url": "https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/javascript",
      "title": "Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string",
      "answer": "const remove = s =>; s.replace(/!+/g, \"\")+\"!\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bcfb44255c74a39d81f4\")",
      "url": "https://www.codewars.com/kata/jennys-secret-message/javascript",
      "title": "Jenny's secret message",
      "answer": "function greet(name){  return \"Hello, \" + (name == \"Johnny\" ? \"my love\" : name) + \"!\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd0244255c74a39d81f5\")",
      "url": "https://www.codewars.com/kata/how-many-lightsabers-do-you-own/javascript",
      "title": "How many lightsabers do you own?",
      "answer": "function howManyLightsabersDoYouOwn(name) {  return name === 'Zach' ? 18 : 0;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd0844255c74a39d81f6\")",
      "url": "https://www.codewars.com/kata/convert-a-string-to-an-array/javascript",
      "title": "Convert a string to an array",
      "answer": "function stringToArray(string){  return string.split(' ');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd0e44255c74a39d81f7\")",
      "url": "https://www.codewars.com/kata/last/javascript",
      "title": "Last",
      "answer": "function last(list){  var last = arguments[arguments.length - 1];  return last[last.length - 1] || last;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd1344255c74a39d81f8\")",
      "url": "https://www.codewars.com/kata/bash-basics-while-loop/javascript",
      "title": "Bash Basics - While Loop",
      "answer": "echo \"Count: \"{1..20}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd1944255c74a39d81f9\")",
      "url": "https://www.codewars.com/kata/sort-and-star/javascript",
      "title": "Sort and Star",
      "answer": "function twoSort(s) {  return s.sort()[0].split('').join('***');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd2144255c74a39d81fa\")",
      "url": "https://www.codewars.com/kata/convert-number-to-reversed-array-of-digits/javascript",
      "title": "Convert number to reversed array of digits",
      "answer": "function digitize(n){  return (n + '').split('').map(Number).reverse();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd2544255c74a39d81fb\")",
      "url": "https://www.codewars.com/kata/es6-string-addition/javascript",
      "title": "ES6 string addition",
      "answer": "function joinStrings(string1, string2){   return `${string1} ${string2}`}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd2a44255c74a39d81fc\")",
      "url": "https://www.codewars.com/kata/grasshopper-basic-function-fixer/javascript",
      "title": "Grasshopper - Basic Function Fixer",
      "answer": "function addFive(num) {  return num + 5;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd3044255c74a39d81fd\")",
      "url": "https://www.codewars.com/kata/for-ufc-fans-total-beginners-conor-mcgregor-vs-george-saint-pierre/javascript",
      "title": "For UFC Fans (Total Beginners): Conor McGregor vs George Saint Pierre",
      "answer": "var quote = function(fighter) {  switch(fighter.toLowerCase()) {    case 'conor mcgregor': return \"I'd like to take this chance to apologize.. To absolutely NOBODY!\";    case 'george saint pierre': return \"I am not impressed by your performance.\";    default : 'Who are you?'   }};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd3644255c74a39d81fe\")",
      "url": "https://www.codewars.com/kata/simple-multiplication/javascript",
      "title": "Simple multiplication",
      "answer": "function simpleMultiplication(n) {    return n * (n % 2 ? 9 : 8);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd3b44255c74a39d81ff\")",
      "url": "https://www.codewars.com/kata/basic-making-six-toast/javascript",
      "title": "BASIC: Making Six Toast.",
      "answer": "function sixToast(num) {  return Math.abs(num-6)}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd4044255c74a39d8200\")",
      "url": "https://www.codewars.com/kata/duck-duck-goose/javascript",
      "title": "Duck Duck Goose",
      "answer": "function duckDuckGoose(players, goose) {    return players[(goose-1)%players.length].name}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd4644255c74a39d8201\")",
      "url": "https://www.codewars.com/kata/remove-first-and-last-character/javascript",
      "title": "Remove First and Last Character",
      "answer": "function removeChar(str) {  return str.slice(1, -1);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd4b44255c74a39d8202\")",
      "url": "https://www.codewars.com/kata/hello-f-number/javascript",
      "title": "Hello F#",
      "answer": "let hello = function    | Some name ->; \"Hello, \" + name    | None ->; \"Hello World\"",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd5144255c74a39d8203\")",
      "url": "https://www.codewars.com/kata/keep-hydrated-1/javascript",
      "title": "Keep Hydrated!",
      "answer": "function litres(time) {  return Math.floor(time * 0.5);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd5844255c74a39d8204\")",
      "url": "https://www.codewars.com/kata/switch-it-up/javascript",
      "title": "Switch it Up!",
      "answer": "switchItUp=n=>;[\"Zero\",\"One\",\"Two\",\"Three\",\"Four\",\"Five\",\"Six\",\"Seven\",\"Eight\",\"Nine\"][n]",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd5e44255c74a39d8205\")",
      "url": "https://www.codewars.com/kata/find-maximum-and-minimum-values-of-a-list/javascript",
      "title": "Find Maximum and Minimum Values of a List",
      "answer": "const min = (list) =>; Math.min(...list);const max = (list) =>; Math.max(...list);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd6444255c74a39d8206\")",
      "url": "https://www.codewars.com/kata/classic-hello-world/javascript",
      "title": "Classic Hello World",
      "answer": "class Solution{  static main() {    console.log(\"Hello World!\");  }  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd6944255c74a39d8207\")",
      "url": "https://www.codewars.com/kata/find-maximum-and-minimum-values-of-a-list/javascript",
      "title": "Find Maximum and Minimum Values of a List",
      "answer": "const min = (list) =>; Math.min(...list);const max = (list) =>; Math.max(...list);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd6f44255c74a39d8208\")",
      "url": "https://www.codewars.com/kata/find-the-position/javascript",
      "title": "Find the position!",
      "answer": "function position(letter){  const alphabet = 'abcdefghijklmnopqrstuvwxyz';  return 'Position of alphabet: ' + (alphabet.indexOf(letter) + 1);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd7444255c74a39d8209\")",
      "url": "https://www.codewars.com/kata/parse-float/javascript",
      "title": "Parse float",
      "answer": "function parseF(s) {  return isNaN(parseFloat(s)) ? null : parseFloat(s);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd7b44255c74a39d820a\")",
      "url": "https://www.codewars.com/kata/simple-calculator/javascript",
      "title": "simple calculator ",
      "answer": "function calculator(a,b,sign){  if ((typeof a === \"number\") &amp;&amp; (typeof b === \"number\")) {    switch (sign) {    case \"+\":      return a + b;    case \"-\":      return a - b;    case \"*\":      return a * b;    case \"/\":      return a / b;    }  }  return \"unknown value\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd8144255c74a39d820b\")",
      "url": "https://www.codewars.com/kata/whats-up-next/javascript",
      "title": "What's up next?",
      "answer": "function nextItem(xs, item) {  var found = false;  for (var x of xs) {    if (found) return x;    if (x == item) found = true;  }  return undefined;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd8944255c74a39d820c\")",
      "url": "https://www.codewars.com/kata/counting-sheep-dot-dot-dot/javascript",
      "title": "Counting sheep...",
      "answer": "function countSheeps(arrayOfSheeps) {  return arrayOfSheeps.filter(Boolean).length;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd9044255c74a39d820d\")",
      "url": "https://www.codewars.com/kata/convert-a-number-to-a-string/javascript",
      "title": "Convert a Number to a String!",
      "answer": "function numberToString(num) {  return num.toString();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bd9644255c74a39d820e\")",
      "url": "https://www.codewars.com/kata/dna-to-rna-conversion/javascript",
      "title": "DNA to RNA Conversion",
      "answer": "function DNAtoRNA(dna){  return dna.replace(/T/g, 'U');}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bda444255c74a39d820f\")",
      "url": "https://www.codewars.com/kata/convert-a-number-to-a-string/javascript",
      "title": "Convert a Number to a String!",
      "answer": "function numberToString(num) {  return num.toString();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdaa44255c74a39d8210\")",
      "url": "https://www.codewars.com/kata/the-if-function/javascript",
      "title": "The 'if' function",
      "answer": "function _if(bool, func1, func2) {  return bool ? func1() : func2();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdb044255c74a39d8211\")",
      "url": "https://www.codewars.com/kata/find-nth-digit-of-a-number/javascript",
      "title": "Find n'th Digit of a Number",
      "answer": "var findDigit = function(num, nth){    if(nth <= 0)      return -1;         var x = Math.abs(num);    for (var i=1; i < nth; i++){      x = Math.floor(x/10);    }    return x%10;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdb444255c74a39d8212\")",
      "url": "https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/javascript",
      "title": "Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string",
      "answer": "const remove = s =>; s.replace(/!+/g, \"\")+\"!\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdbc44255c74a39d8213\")",
      "url": "https://www.codewars.com/kata/fix-the-bugs-syntax-my-first-kata/javascript",
      "title": "Fix the Bugs (Syntax) - My First Kata",
      "answer": "function myFirstKata(a, b) {  if (typeof(a) !== \"number\" || typeof(b) !== \"number\")    return false;  else    return a % b + b % a;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdc344255c74a39d8214\")",
      "url": "https://www.codewars.com/kata/count-of-positives-slash-sum-of-negatives/javascript",
      "title": "Count of positives / sum of negatives",
      "answer": "function countPositivesSumNegatives(input) {    if (input == null || input.length == 0)      return [];        var positive = 0;    var negative = 0;        for (var i=0, l=input.length; i<l; ++i)    {      if (input[i] >; 0)        ++ positive;      else        negative += input[i];    }        return [positive, negative];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdc844255c74a39d8215\")",
      "url": "https://www.codewars.com/kata/compare-within-margin/javascript",
      "title": "Compare within margin",
      "answer": "function closeCompare(a, b, m = 0){  return Math.abs(a - b) <= m? 0: Math.sign(a - b);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdcd44255c74a39d8216\")",
      "url": "https://www.codewars.com/kata/is-the-string-uppercase/javascript",
      "title": "Is the string uppercase?",
      "answer": "String.prototype.isUpperCase=function() {return this==this.toUpperCase()}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdd244255c74a39d8217\")",
      "url": "https://www.codewars.com/kata/filling-an-array-part-1/javascript",
      "title": "Filling an array (part 1)",
      "answer": "const arr = n =>; Array.from({length: n}, (_, i) =>; i);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdd744255c74a39d8218\")",
      "url": "https://www.codewars.com/kata/remove-duplicates-from-list/javascript",
      "title": "Remove duplicates from list",
      "answer": "function distinct(a) {  return [...new Set(a)];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bddd44255c74a39d8219\")",
      "url": "https://www.codewars.com/kata/evil-or-odious/javascript",
      "title": "Evil or Odious",
      "answer": "evil = n =>; [\"It's Evil!\", \"It's Odious!\"][(n.toString(2).split(\"1\").length-1) &amp; 1];",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bde244255c74a39d821a\")",
      "url": "https://www.codewars.com/kata/hex-to-decimal/javascript",
      "title": "Hex to Decimal",
      "answer": "function hexToDec(hexString){ return  parseInt(hexString, 16);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bde844255c74a39d821b\")",
      "url": "https://www.codewars.com/kata/chuck-norris-vii-true-or-false-beginner/javascript",
      "title": "Chuck Norris VII - True or False? (Beginner)",
      "answer": "function ifChuckSaysSo() {  return !1;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bded44255c74a39d821c\")",
      "url": "https://www.codewars.com/kata/exclusive-or-xor-logical-operator/javascript",
      "title": "Exclusive \"or\" (xor) Logical Operator",
      "answer": "function xor(a, b) {  return a != b;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdf444255c74a39d821d\")",
      "url": "https://www.codewars.com/kata/plural/javascript",
      "title": "Plural",
      "answer": "function plural(n) {  return n !== 1;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bdfa44255c74a39d821e\")",
      "url": "https://www.codewars.com/kata/count-the-monkeys/javascript",
      "title": "Count the Monkeys!",
      "answer": "function monkeyCount(n) { var monkeys = []; for(var i=1; i<n+1; i++){   monkeys.push(i); } return monkeys;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be0144255c74a39d821f\")",
      "url": "https://www.codewars.com/kata/get-the-mean-of-an-array/javascript",
      "title": "Get the mean of an array",
      "answer": "function getAverage(marks){  return Math.floor(marks.reduce((sum, x) =>; sum + x) / marks.length);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be0844255c74a39d8220\")",
      "url": "https://www.codewars.com/kata/a-needle-in-the-haystack/javascript",
      "title": "A Needle in the Haystack",
      "answer": "function findNeedle(haystack) {  return \"found the needle at position \" + haystack.indexOf(\"needle\");}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be0c44255c74a39d8221\")",
      "url": "https://www.codewars.com/kata/sql-basics-simple-distinct/javascript",
      "title": "SQL Basics: Simple DISTINCT",
      "answer": "SELECT DISTINCT ageFROM people",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be1244255c74a39d8222\")",
      "url": "https://www.codewars.com/kata/beginner-reduce-but-grow/javascript",
      "title": "Beginner - Reduce but Grow",
      "answer": "const grow=x=>; x.reduce((a,b) =>; a*b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be1844255c74a39d8223\")",
      "url": "https://www.codewars.com/kata/sql-basics-simple-min-slash-max/javascript",
      "title": "SQL Basics: Simple MIN / MAX",
      "answer": "SELECT       MIN(age) AS age_min,      MAX(age) AS age_maxFROM    people",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be1d44255c74a39d8224\")",
      "url": "https://www.codewars.com/kata/sql-basics-simple-sum/javascript",
      "title": "SQL Basics: Simple SUM",
      "answer": "SELECT SUM(age) AS age_sum FROM people",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be2244255c74a39d8225\")",
      "url": "https://www.codewars.com/kata/get-number-from-string/javascript",
      "title": "Get number from string",
      "answer": "function getNumberFromString(s) {  return +s.replace(/\\D/g, \"\");}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be2844255c74a39d8226\")",
      "url": "https://www.codewars.com/kata/tip-calculator/javascript",
      "title": "Tip Calculator",
      "answer": "const TIPS = {  \"terrible\": 0.0,  \"poor\": 0.05,  \"good\": 0.1,  \"great\": 0.15,  \"excellent\": 0.2};const calculateTip = (amount, rating) =>; {  rating = rating.toLowerCase();    return rating in TIPS ? Math.ceil(TIPS[rating] * amount) : \"Rating not recognised\";};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be3044255c74a39d8227\")",
      "url": "https://www.codewars.com/kata/alternating-case-%3C-equals-%3E-alternating-case/javascript",
      "title": "altERnaTIng cAsE <=>; ALTerNAtiNG CaSe",
      "answer": "String.prototype.toAlternatingCase = function () {    return this.split(\"\").map(a =>; a === a.toUpperCase()? a.toLowerCase(): a.toUpperCase()).join('')}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be3544255c74a39d8228\")",
      "url": "https://www.codewars.com/kata/alan-partridge-ii-apple-turnover/javascript",
      "title": "Alan Partridge II - Apple Turnover",
      "answer": "apple=x=>;x*x>;1000?\"It's hotter than the sun!!\":\"Help yourself to a honeycomb Yorkie for the glovebox.\"",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be3a44255c74a39d8229\")",
      "url": "https://www.codewars.com/kata/1-find-all-active-students/javascript",
      "title": "1. Find all active students",
      "answer": "SELECT * FROM students WHERE IsActive;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be3f44255c74a39d822a\")",
      "url": "https://www.codewars.com/kata/sql-basics-simple-where-and-order-by/javascript",
      "title": "SQL Basics: Simple WHERE and ORDER BY",
      "answer": "SELECT *  FROM people  WHERE age >; 50  ORDER BY age DESC",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be4544255c74a39d822b\")",
      "url": "https://www.codewars.com/kata/squash-the-bugs/javascript",
      "title": "Squash the bugs",
      "answer": "function findLongest(str) {  var spl = str.split(\" \"),      longest = 0;    for (var i in spl) {    if (spl[i].length >; longest) {      longest = spl[i].length;    }  }  return longest;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be4b44255c74a39d822c\")",
      "url": "https://www.codewars.com/kata/is-this-my-tail/javascript",
      "title": "Is this my tail?",
      "answer": "function correctTail(bod, tail) {  return bod[bod.length-1] === tail}      ",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be5144255c74a39d822d\")",
      "url": "https://www.codewars.com/kata/my-head-is-at-the-wrong-end/javascript",
      "title": "My head is at the wrong end!",
      "answer": "function fixTheMeerkat(arr) {  return arr.reverse();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be5644255c74a39d822e\")",
      "url": "https://www.codewars.com/kata/transportation-on-vacation/javascript",
      "title": "Transportation on vacation ",
      "answer": "const rentalCarCost = d =>; d * 40 - ((d >; 6) ? 50 : ((d >; 2) ? 20 : 0));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be5c44255c74a39d822f\")",
      "url": "https://www.codewars.com/kata/string-repeat/javascript",
      "title": "String repeat",
      "answer": "function repeatStr (n, s) {  return s.repeat(n);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be6244255c74a39d8230\")",
      "url": "https://www.codewars.com/kata/grasshopper-personalized-message/javascript",
      "title": "Grasshopper - Personalized Message",
      "answer": "function greet (name, owner) {  return name === owner ? 'Hello boss' :   'Hello guest';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be6844255c74a39d8231\")",
      "url": "https://www.codewars.com/kata/generate-range-of-integers/javascript",
      "title": "Generate range of integers",
      "answer": "function generateRange(min, max, step){  let arr = [];  for (let i=min; i<=max; i += step) {    arr.push(i);  }  return arr;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be6e44255c74a39d8232\")",
      "url": "https://www.codewars.com/kata/validate-code-with-simple-regex/javascript",
      "title": "validate code with simple regex",
      "answer": "function validateCode (code) {return /^[123]/.test(code)}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be7344255c74a39d8233\")",
      "url": "https://www.codewars.com/kata/did-she-say-hallo/javascript",
      "title": "Did she say hallo?",
      "answer": "const validateHello = greetings =>; /h[ae]llo|ciao|salut|hola|ahoj|czesc/i.test(greetings);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be7944255c74a39d8234\")",
      "url": "https://www.codewars.com/kata/they-say-that-only-the-name-is-long-enough-to-attract-attention-they-also-said-that-only-a-simple-kata-will-have-someone-to-solve-it-this-is-a-sadly-story-number-1-are-they-opposite/javascript",
      "title": "They say that only the name is long enough to attract attention. They also said that only a simple Kata will have someone to solve it. This is a sadly story #1: Are they opposite?",
      "answer": "function isOpposite(s1,s2){  if(s1 === s2 || s1.toLowerCase() !== s2.toLowerCase()) return false;    for(var i = 0; i < s1.length; i++) {    if(s1.charAt(i) === s2.charAt(i)) return false;  }    return true;  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be7e44255c74a39d8235\")",
      "url": "https://www.codewars.com/kata/function-3-multiplying-two-numbers/javascript",
      "title": "Function 3 - multiplying two numbers",
      "answer": "function multiply(a, b){  if(typeof a == 'number' &amp;&amp; typeof b == 'number')    return a * b;  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be8344255c74a39d8236\")",
      "url": "https://www.codewars.com/kata/age-range-compatibility-equation/javascript",
      "title": "Age Range Compatibility Equation",
      "answer": "function datingRange(age){  return `${min(age)}-${max(age)}`;    function min(age) {    return Math.floor(age >; 14 ? (age / 2) + 7 : age - 0.10 * age);  }    function max(age) {    return Math.floor(age >; 14 ? (age - 7) * 2 : age + 0.10 * age);  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be8944255c74a39d8237\")",
      "url": "https://www.codewars.com/kata/merging-sorted-integer-arrays-without-duplicates/javascript",
      "title": "Merging sorted integer arrays (without duplicates)",
      "answer": "def merge_arrays(a, b)  (a | b).sortend",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be8f44255c74a39d8238\")",
      "url": "https://www.codewars.com/kata/simple-comparison/javascript",
      "title": "Simple Comparison? ",
      "answer": "function add(a, b){  return a == b }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0be9a44255c74a39d8239\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bea044255c74a39d823a\")",
      "url": "https://www.codewars.com/kata/beginner-lost-without-a-map/javascript",
      "title": "Beginner - Lost Without a Map",
      "answer": "function maps(x){  return x.map(n =>; n * 2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bea544255c74a39d823b\")",
      "url": "https://www.codewars.com/kata/the-wide-mouthed-frog/javascript",
      "title": "The Wide-Mouthed frog! ",
      "answer": "function mouthSize(animal) {  return animal.toLowerCase() == 'alligator' ? 'small' : 'wide';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0beaa44255c74a39d823c\")",
      "url": "https://www.codewars.com/kata/well-of-ideas-easy-version/javascript",
      "title": "Well of Ideas - Easy Version",
      "answer": "const well = x =>; {  const good_count = x.filter(x =>; x == 'good').length;  return good_count < 1 ? 'Fail!' :          good_count < 3 ? 'Publish!' : 'I smell a series!';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0beaf44255c74a39d823d\")",
      "url": "https://www.codewars.com/kata/sum-mixed-array/javascript",
      "title": "Sum Mixed Array",
      "answer": "function sumMix(x){  return x.map(a =>; +a).reduce((a, b) =>; a + b);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0beb444255c74a39d823e\")",
      "url": "https://www.codewars.com/kata/bin-to-decimal/javascript",
      "title": "Bin to Decimal",
      "answer": "function binToDec(bin){  return parseInt(bin,2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bebc44255c74a39d823f\")",
      "url": "https://www.codewars.com/kata/calculate-bmi/javascript",
      "title": "Calculate BMI",
      "answer": "bmi = (w, h) =>; (w = w / h / h) >; 30 ? 'Obese' : w >; 25 ? 'Overweight' : w >; 18.5 ? 'Normal' : 'Underweight';",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bec144255c74a39d8240\")",
      "url": "https://www.codewars.com/kata/filter-out-the-geese/javascript",
      "title": "Filter out the geese",
      "answer": "function gooseFilter (birds) {  var geese = [\"African\", \"Roman Tufted\", \"Toulouse\", \"Pilgrim\", \"Steinbacher\"];  return birds.filter(b =>; !geese.includes(b));};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bec644255c74a39d8241\")",
      "url": "https://www.codewars.com/kata/abbreviate-a-two-word-name/javascript",
      "title": "Abbreviate a Two Word Name",
      "answer": "function abbrevName(name){  var nameArray = name.split(\" \");  return (nameArray[0][0] + \".\" + nameArray[1][0]).toUpperCase();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0becb44255c74a39d8242\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bed044255c74a39d8243\")",
      "url": "https://www.codewars.com/kata/string-cleaning/javascript",
      "title": "String cleaning",
      "answer": "function stringClean(s){  return s.replace(/\\d/g, \"\");}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bed744255c74a39d8244\")",
      "url": "https://www.codewars.com/kata/swap-values/javascript",
      "title": "Swap Values",
      "answer": "function swapValues() {  return arguments[0].reverse();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bedc44255c74a39d8245\")",
      "url": "https://www.codewars.com/kata/makelowercase/javascript",
      "title": "MakeLowerCase",
      "answer": "module MakeLower whereimport Data.Char (toLower)makeLowerCase :: String ->; StringmakeLowerCase = map toLower",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bee244255c74a39d8246\")",
      "url": "https://www.codewars.com/kata/classy-extentions/javascript",
      "title": "Classy Extentions",
      "answer": "class Cat extends Animal {  speak() {    return `${this.name} meows.`;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bee844255c74a39d8247\")",
      "url": "https://www.codewars.com/kata/parse-nice-int-from-char-problem/javascript",
      "title": "Parse nice int from char problem",
      "answer": "function getAge(inputString){  return parseInt(inputString);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0beec44255c74a39d8248\")",
      "url": "https://www.codewars.com/kata/is-there-a-vowel-in-there/javascript",
      "title": "Is there a vowel in there?",
      "answer": "function isVow(a){  for (var i=0, l=a.length; i<l; ++i)  {    var char = String.fromCharCode(a[i])    if ('aeiou'.indexOf(char) !== -1)    a[i] = char;  }    return a;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bef144255c74a39d8249\")",
      "url": "https://www.codewars.com/kata/return-two-highest-values-in-list/javascript",
      "title": "Return Two Highest Values in List",
      "answer": "def two_highest(ls):    result = sorted(list(set(ls)), reverse=True)[:2]    return result if isinstance(ls, (list)) else False",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bef744255c74a39d824a\")",
      "url": "https://www.codewars.com/kata/ghost-code/javascript",
      "title": "Ghost code?!",
      "answer": "public class GhostCode{  public static String helloName(final String name){    if(name == null || name.equals(\"\"))      return \"Hello world!\";    else      return \"Hello my name is \" + name;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0befc44255c74a39d824b\")",
      "url": "https://www.codewars.com/kata/uefa-euro-2016/javascript",
      "title": "UEFA EURO 2016",
      "answer": "function uefaEuro2016(commands, scores){  // your code...  if (scores[0] == scores[1])    return `At match ${commands[0]} - ${commands[1]}, commands played draw.`;  if (scores[0] < scores[1])    return `At match ${commands[0]} - ${commands[1]}, ${commands[1]} won!`;  return `At match ${commands[0]} - ${commands[1]}, ${commands[0]} won!`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf0144255c74a39d824c\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf0944255c74a39d824d\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf1644255c74a39d824e\")",
      "url": "https://www.codewars.com/kata/grasshopper-variable-assignment-debug/javascript",
      "title": "Grasshopper - Variable Assignment Debug",
      "answer": "var a = \"dev\"var b = \"Lab\"var name = a + b",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf1b44255c74a39d824f\")",
      "url": "https://www.codewars.com/kata/simple-validation-of-a-username-with-regex/javascript",
      "title": "simple validation of a username with regex",
      "answer": "function validateUsr(username) {  return /^[0-9a-z_]{4,16}$/.test(username)}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf2044255c74a39d8250\")",
      "url": "https://www.codewars.com/kata/basic-variable-assignment/javascript",
      "title": "Basic variable assignment",
      "answer": "var a = \"code\";var b = \"wa.rs\";var name = a + b;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf2844255c74a39d8251\")",
      "url": "https://www.codewars.com/kata/find-the-remainder/javascript",
      "title": "Find the Remainder",
      "answer": "function remainder(a, b){  return a >; b ? a % b : b % a;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf2d44255c74a39d8252\")",
      "url": "https://www.codewars.com/kata/collatz-conjecture-3n-plus-1/javascript",
      "title": "Collatz Conjecture (3n+1)",
      "answer": "var hotpo = function(n, acc = 0) {  if (n <= 1) {    return acc;  } else {    return hotpo(n%2==0 ? n/2 : 3*n+1, acc+1);  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf3444255c74a39d8253\")",
      "url": "https://www.codewars.com/kata/is-the-date-today/javascript",
      "title": "Is the date today",
      "answer": "function isToday(date) {  return new Date().toDateString() === date.toDateString();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf3b44255c74a39d8254\")",
      "url": "https://www.codewars.com/kata/pirates-are-the-cannons-ready/javascript",
      "title": "Pirates!! Are the Cannons ready!??",
      "answer": "const cannonsReady = (gunners) =>; {  return Object.values(gunners).some(m =>; m === 'nay') ? 'Shiver me timbers!' : 'Fire!';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf4144255c74a39d8255\")",
      "url": "https://www.codewars.com/kata/do-i-get-a-bonus/javascript",
      "title": "Do I get a bonus?",
      "answer": "function bonusTime(salary, bonus) {  return bonus ? `£${10 * salary}` : `£${salary}`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf4744255c74a39d8256\")",
      "url": "https://www.codewars.com/kata/grasshopper-combine-strings/javascript",
      "title": "Grasshopper - Combine strings",
      "answer": "const combineNames = (...names) =>; names.join(' ');",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf4d44255c74a39d8257\")",
      "url": "https://www.codewars.com/kata/area-of-a-square-easy/javascript",
      "title": "Area of a Square (Easy)",
      "answer": "function squareArea(A){  var circum = 4 * A;  var radius = circum / (2 * Math.PI);  var area = Math.pow(radius, 2);  return Math.round(area*100)/100}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf5344255c74a39d8258\")",
      "url": "https://www.codewars.com/kata/points-of-reflection/javascript",
      "title": "Points of Reflection",
      "answer": "const symmetricPoint = ([a, b], [c, d]) =>; [c * 2 - a, d * 2 - b];",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf5844255c74a39d8259\")",
      "url": "https://www.codewars.com/kata/determine-offspring-sex-based-on-genes-xx-and-xy-chromosomes/javascript",
      "title": "Determine offspring sex based on genes XX and XY chromosomes",
      "answer": "function chromosomeCheck(sperm) {  return `Congratulations! You're going to have a ${sperm === 'XY' ? 'son' : 'daughter'}.`}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf5e44255c74a39d825a\")",
      "url": "https://www.codewars.com/kata/formatting-decimal-places-number-0/javascript",
      "title": "Formatting decimal places #0",
      "answer": "const twoDecimalPlaces = n =>;  Number(n.toFixed(2))",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf6344255c74a39d825b\")",
      "url": "https://www.codewars.com/kata/grasshopper-if-slash-else-syntax-debug/javascript",
      "title": "Grasshopper - If/else syntax debug",
      "answer": "function checkAlive(health) {  return health >; 0;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf6744255c74a39d825c\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf6e44255c74a39d825d\")",
      "url": "https://www.codewars.com/kata/grasshopper-summation/javascript",
      "title": "Grasshopper - Summation",
      "answer": "const summation = n =>; n * (n + 1) / 2;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf7444255c74a39d825e\")",
      "url": "https://www.codewars.com/kata/printing-array-elements-with-comma-delimiters/javascript",
      "title": "Printing Array elements with Comma delimiters",
      "answer": "function printArray(array){  return array.join();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf7a44255c74a39d825f\")",
      "url": "https://www.codewars.com/kata/short-long-short/javascript",
      "title": "Short Long Short",
      "answer": "function solution(a, b) {  return a.length < b.length ? a + b + a : b + a + b}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf8144255c74a39d8260\")",
      "url": "https://www.codewars.com/kata/correct-the-mistakes-of-the-character-recognition-software/javascript",
      "title": "Correct the mistakes of the character recognition software",
      "answer": "correct = s =>; s.replace(/0/g,'O').replace(/1/g,'I').replace(/5/g,'S')",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf8744255c74a39d8261\")",
      "url": "https://www.codewars.com/kata/price-of-mangoes/javascript",
      "title": "Price of Mangoes",
      "answer": "function mango(quantity, price){  return price * (quantity - Math.floor(quantity / 3));}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf8d44255c74a39d8262\")",
      "url": "https://www.codewars.com/kata/fuel-calculator/javascript",
      "title": "Fuel Calculator ",
      "answer": "function fuelPrice(litres, pricePerLiter) {  for (var i = 2; i <= 10; i +=2) { //discount loop    if (litres >;= i) {      pricePerLiter -= 0.05;    }  }  return Math.round(litres * pricePerLiter * 100) / 100;;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf9344255c74a39d8263\")",
      "url": "https://www.codewars.com/kata/days-in-the-year/javascript",
      "title": "Days in the year",
      "answer": "function yearDays(year) {  return year + ' has ' + (!(year % 100) &amp;&amp; year % 400 || year % 4 ? '365' : '366') + ' days';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf9844255c74a39d8264\")",
      "url": "https://www.codewars.com/kata/is-it-a-palindrome/javascript",
      "title": "Is it a palindrome?",
      "answer": "module Palindroms whereimport Data.Char (toLower)isPalindrom :: String ->; BoolisPalindrom = (reverse >;>;= (==)) . map toLower",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bf9c44255c74a39d8265\")",
      "url": "https://www.codewars.com/kata/fuel-calculator/javascript",
      "title": "Fuel Calculator ",
      "answer": "function fuelPrice(litres, pricePerLiter) {  for (var i = 2; i <= 10; i +=2) { //discount loop    if (litres >;= i) {      pricePerLiter -= 0.05;    }  }  return Math.round(litres * pricePerLiter * 100) / 100;;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfa144255c74a39d8266\")",
      "url": "https://www.codewars.com/kata/polish-alphabet/javascript",
      "title": "Polish alphabet",
      "answer": "function correctPolishLetters (string) {  var dict = {'ą':'a','ć':'c','ę':'e','ł':'l','ń':'n','ó':'o','ś':'s','ź':'z','ż':'z'};  return string.replace(/[ąćęłńóśźż]/g, match =>; dict[match]);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfa644255c74a39d8267\")",
      "url": "https://www.codewars.com/kata/whats-the-real-floor/javascript",
      "title": "What's the real floor?",
      "answer": "function getRealFloor(n) {  // Less than 1, return n  if (n <= 0) return n;    return n - (n >;= 13 ? 2 : 1);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfac44255c74a39d8268\")",
      "url": "https://www.codewars.com/kata/miles-per-gallon-to-kilometers-per-liter/javascript",
      "title": "Miles per gallon to kilometers per liter",
      "answer": "var LITRES_PER_GALLON = 4.54609188;var KILOMETERS_PER_MILE = 1.609344;function converter (mpg) {  return Math.round(100 * mpg * KILOMETERS_PER_MILE / LITRES_PER_GALLON) / 100;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfb244255c74a39d8269\")",
      "url": "https://www.codewars.com/kata/count-the-number-of-cubes-with-paint-on/javascript",
      "title": "Count the number of cubes with paint on",
      "answer": "let countSquares = c =>; c ? 6 * c * c + 2 : 1;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfb944255c74a39d826a\")",
      "url": "https://www.codewars.com/kata/count-of-positives-slash-sum-of-negatives/javascript",
      "title": "Count of positives / sum of negatives",
      "answer": "function countPositivesSumNegatives(input) {    if (input == null || input.length == 0)      return [];        var positive = 0;    var negative = 0;        for (var i=0, l=input.length; i<l; ++i)    {      if (input[i] >; 0)        ++ positive;      else        negative += input[i];    }        return [positive, negative];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfbf44255c74a39d826b\")",
      "url": "https://www.codewars.com/kata/leonardo-dicaprio-and-oscars/javascript",
      "title": "Leonardo Dicaprio and Oscars",
      "answer": "const leo = (oscar) =>; {  return oscar === 88 ? 'Leo finally won the oscar! Leo is happy' :         oscar === 86 ? 'Not even for Wolf of wallstreet?!'       :         oscar  <  88 ? 'When will you give Leo an Oscar?'        :         'Leo got one already!';};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfc344255c74a39d826c\")",
      "url": "https://www.codewars.com/kata/is-your-period-late/javascript",
      "title": "Is your period late?",
      "answer": "var _MS_PER_DAY = 1000 * 60 * 60 * 24;function periodIsLate(last, today, cycleLength){  return Math.floor((today - last) / _MS_PER_DAY) >; cycleLength;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfc944255c74a39d826d\")",
      "url": "https://www.codewars.com/kata/lario-and-muigi-pipe-problem/javascript",
      "title": "Lario and Muigi Pipe Problem",
      "answer": "function pipeFix(numbers){  var first = numbers[0];  var last = numbers[numbers.length-1];    var arr = [];  for(var i = first; i <= last; i++) {    arr.push(i);  }  return arr;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfce44255c74a39d826e\")",
      "url": "https://www.codewars.com/kata/pole-vault-starting-marks/javascript",
      "title": "Pole Vault Starting Marks",
      "answer": "function startingMark(bodyHeight){  // Remember: Body height of 1.52 m -->; starting mark: 9.45 m  //           Body height of 1.83 m -->; starting mark: 10.67 m  // All other starting marks are based on these guidelines!    var m = (10.67 - 9.45) / (1.83 - 1.52);  return Math.round((10.67 + m * bodyHeight - m * 1.83) * 100) / 100;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfd444255c74a39d826f\")",
      "url": "https://www.codewars.com/kata/remove-the-time/javascript",
      "title": "Remove the time",
      "answer": "function shortenToDate(longDate) {  return longDate.split(\",\")[0];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfd944255c74a39d8270\")",
      "url": "https://www.codewars.com/kata/surface-area-and-volume-of-a-box/javascript",
      "title": "Surface Area and Volume of a Box",
      "answer": "const getSize = (w, h, d) =>; [  (w * h + w * d + h * d) * 2,  w * h * d];",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfde44255c74a39d8271\")",
      "url": "https://www.codewars.com/kata/101-dalmatians-squash-the-bugs-not-the-dogs/javascript",
      "title": "101 Dalmatians - squash the bugs, not the dogs!",
      "answer": "function howManyDalmatians(number){  if (number <= 10) {    return \"Hardly any\"  } else if (number <= 50) {    return \"More than a handful!\"  } else if (number === 101) {    return \"101 DALMATIANS!!!\"  } else {    return \"Woah that's a lot of dogs!\"   }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfe344255c74a39d8272\")",
      "url": "https://www.codewars.com/kata/crash-override/javascript",
      "title": "Crash Override",
      "answer": "const initialCap = (str) =>; str[0].toUpperCase();const isValidName = (name) =>; /^[a-z]/i.test(name);const aliasGen = (fName, lName) =>; {  return (isValidName(fName) &amp;&amp; isValidName(lName))    ? `${ firstName[initialCap(fName)] } ${ surname[initialCap(lName)] }`    : 'Your name must start with a letter from A - Z.';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfe944255c74a39d8273\")",
      "url": "https://www.codewars.com/kata/find-the-slope/javascript",
      "title": "Find the Slope",
      "answer": "function slope([ x1, y1, x2, y2 ]) {  let slope = (y2 - y1) / (x2 - x1);  return Number.isFinite(slope) ? `${slope}` : 'undefined';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bfef44255c74a39d8274\")",
      "url": "https://www.codewars.com/kata/welcome/javascript",
      "title": "Welcome!",
      "answer": "function greet(lang) {  return langs[lang]||langs['english'];}var langs = {'english': 'Welcome','czech': 'Vitejte','danish': 'Velkomst','dutch': 'Welkom','estonian': 'Tere tulemast','finnish': 'Tervetuloa','flemish': 'Welgekomen','french': 'Bienvenue','german': 'Willkommen','irish': 'Failte','italian': 'Benvenuto','latvian': 'Gaidits','lithuanian': 'Laukiamas','polish': 'Witamy','spanish': 'Bienvenido','swedish': 'Valkommen','welsh': 'Croeso'};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bff644255c74a39d8275\")",
      "url": "https://www.codewars.com/kata/removing-elements/javascript",
      "title": "Removing Elements",
      "answer": "function removeEveryOther(arr){  return arr.filter(function(elem, index) {    return index % 2 === 0;  });}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0bffc44255c74a39d8276\")",
      "url": "https://www.codewars.com/kata/grasshopper-debug-sayhello/javascript",
      "title": "Grasshopper - Debug sayHello",
      "answer": "const sayHello = name =>; `Hello, ${name}`;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c00244255c74a39d8277\")",
      "url": "https://www.codewars.com/kata/how-good-are-you-really/javascript",
      "title": "How good are you really?",
      "answer": "function betterThanAverage(classPoints, yourPoints) {  return yourPoints >; classPoints.reduce((a, b) =>; a + b, 0) / classPoints.length; }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c00a44255c74a39d8278\")",
      "url": "https://www.codewars.com/kata/number-of-people-in-the-bus/javascript",
      "title": "Number of People in the Bus",
      "answer": "const number = (busStops) =>; busStops.reduce((rem, [on, off]) =>; rem + on - off, 0);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c01144255c74a39d8279\")",
      "url": "https://www.codewars.com/kata/localize-the-barycenter-of-a-triangle/javascript",
      "title": "Localize The Barycenter of a Triangle",
      "answer": "const barTriang = ([xA, yA], [xB, yB], [xC, yC]) =>; [Math.round((xA + xB + xC) / .0003) / 10000, Math.round((yA + yB + yC) / .0003) / 10000];",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c01844255c74a39d827a\")",
      "url": "https://www.codewars.com/kata/smallest-unused-id/javascript",
      "title": "Smallest unused ID",
      "answer": "function nextId(ids){  const used = new Set(ids);  for (let i = 0; i <= ids.length; i++) {    if (!used.has(i)) return i;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c01d44255c74a39d827b\")",
      "url": "https://www.codewars.com/kata/playing-with-cubes-ii/javascript",
      "title": "Playing with cubes II",
      "answer": "// This Cube function needs help// change the constructor so that it can take an integer for the side or no argsclass Cube {  constructor(n) {    this.side = n || 0;  }    getSide() { return this.side; }    setSide(n) {    if (!isNaN(n)) {      this.side = Math.abs(n);    }  }  };",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c02244255c74a39d827c\")",
      "url": "https://www.codewars.com/kata/circular-objects-number-1-running-around-in-circles/javascript",
      "title": "Circular Objects #1 - Running around in circles",
      "answer": "circular = {value: 'Hello World'}circular.self = circular;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c02844255c74a39d827d\")",
      "url": "https://www.codewars.com/kata/a-plus-b/javascript",
      "title": "A + B",
      "answer": "public class FirstClass {    public static byte sum (byte a, byte b) {        byte c = (byte) (a + b);        return c;    }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c02d44255c74a39d827e\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c03244255c74a39d827f\")",
      "url": "https://www.codewars.com/kata/how-much-water-do-i-need/javascript",
      "title": "How much water do I need?",
      "answer": "function howMuchWater(L,X,N){  if (N >; 2 * X) return \"Too much clothes\";  if (N < X) return \"Not enough clothes\";  return +(L * 1.1 ** (N - X)).toFixed(2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c03844255c74a39d8280\")",
      "url": "https://www.codewars.com/kata/arguments-to-binary-addition/javascript",
      "title": "Arguments to Binary addition",
      "answer": "function arr2bin(arr){  return arr.reduce((x,y)=>;x+(typeof y==\"number\"?y:0),0).toString(2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c03e44255c74a39d8281\")",
      "url": "https://www.codewars.com/kata/noobcode-02-tricky-questions-primitives-and-operator-precedence/javascript",
      "title": "noobCode 02: TRICKY QUESTIONS , primitives and operator precedence",
      "answer": "const greaterThanLessThan = (a, b, c) =>; a < b < c;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c04344255c74a39d8282\")",
      "url": "https://www.codewars.com/kata/simple-change-machine/javascript",
      "title": "Simple Change Machine ",
      "answer": "function changeMe(moneyIn){  switch (moneyIn) {    case '£5':      var change = Array(25).fill('20p');      return change.join(' ');    case '£2':      var change = Array(10).fill('20p');      return change.join(' ');    case '£1':      var change = Array(5).fill('20p');      return change.join(' ');    case '50p':      return '20p 20p 10p';    case '20p':      return '10p 10p';    default:      return moneyIn;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c04944255c74a39d8283\")",
      "url": "https://www.codewars.com/kata/how-old-will-i-be-in-2099/javascript",
      "title": "How old will I be in 2099?",
      "answer": "function  calculateAge(m, n) {  if(m == n) return 'You were born this very year!';  var year = Math.abs(m-n) == 1 ? 'year' : 'years';  if(m < n) return \"You are \"+(n-m)+' '+year+' old.';  if(m >; n) return \"You will be born in \"+(-n+m)+' '+year+'.';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c04f44255c74a39d8284\")",
      "url": "https://www.codewars.com/kata/fix-the-program-to-return-hello-world-message-object/javascript",
      "title": "Fix the program to return Hello World message object",
      "answer": "function run() {   \"use strict\";    return {       helloWorld: function () {       var str = { message: \"Hello World\" };       return str;    }};}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c05444255c74a39d8285\")",
      "url": "https://www.codewars.com/kata/incorrect-array-remove-method/javascript",
      "title": "Incorrect array_remove method",
      "answer": "def remove_odd_numbers_from_array(a)  a.reject(&amp;:odd?)end",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c05944255c74a39d8286\")",
      "url": "https://www.codewars.com/kata/subtract-the-sum/javascript",
      "title": "Subtract the Sum",
      "answer": "const SubtractSum = () =>; \"apple\";",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c05e44255c74a39d8287\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c06844255c74a39d8288\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c06d44255c74a39d8289\")",
      "url": "https://www.codewars.com/kata/l1-bartender-drinks/javascript",
      "title": "L1: Bartender, drinks!",
      "answer": "function getDrinkByProfession(param){  let map = new Map([      [\"jabroni\", \"Patron Tequila\"],      [\"school counselor\", \"Anything with Alcohol\"],      [\"programmer\", \"Hipster Craft Beer\"],      [\"bike gang member\", \"Moonshine\"],      [\"politician\", \"Your tax dollars\"],      [\"rapper\", \"Cristal\"]      ]);         let normal = param.toLowerCase();   return map.has(normal) ? map.get(normal) : \"Beer\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c07344255c74a39d828a\")",
      "url": "https://www.codewars.com/kata/safen-user-input-part-i-htmlspecialchars/javascript",
      "title": "Safen User Input Part I - htmlspecialchars",
      "answer": "function htmlspecialchars(formData) {  return formData.replace(/&amp;/g, \"&amp;amp;\")                 .replace(/\"/g, \"&amp;quot;\")                 .replace(/</g, \"&amp;lt;\")                 .replace(/>;/g, \"&amp;gt;\");}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c07944255c74a39d828b\")",
      "url": "https://www.codewars.com/kata/be-concise-ii-i-need-squares/javascript",
      "title": "Be Concise II - I Need Squares",
      "answer": "function squaresOnly(a) {  return a.filter(x =>; x ** 0.5 % 1 == 0);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c07d44255c74a39d828c\")",
      "url": "https://www.codewars.com/kata/fun-with-es6-classes-number-4-cubes-and-setters/javascript",
      "title": "Fun with ES6 Classes #4 - Cubes and Setters",
      "answer": "//ES5 typefunction Cube(n) {  this._length = n;  this._surfaceArea = n * n * 6;  this._volume = n * n * n;}Object.defineProperties(Cube.prototype, {    length : {      get: function() {        return this._length      },      set: function(n) {        this._length = n,        this._surfaceArea = n * n * 6,        this._volume = n * n * n;      }    },    surfaceArea : {      get: function() {        return this._surfaceArea      },      set: function(n) {        this._length = Math.sqrt(n / 6),        this._surfaceArea = n,        this._volume = Math.pow(this._length, 3);      }     },     volume : {      get: function() {        return this._volume      },      set: function(n) {        this._length = Math.pow(n, 1 / 3),        this._surfaceArea = this._length * this._length * 6,        this._volume = n;      }    }})//ES6 typeclass ES6Cube {    constructor(n) {      this._length = n,      this._surfaceArea = n * n * 6,      this._volume = n * n * n;    }    get length() {        return this._length    }    set length(n) {        this._length = n,        this._surfaceArea = n * n * 6,        this._volume = n * n * n;    }    get surfaceArea() {        return this._surfaceArea    }    set surfaceArea(n) {        this._length = Math.sqrt(n / 6),        this._surfaceArea = n,        this._volume = Math.pow(this._length, 3);    }    get volume() {        return this._volume    }    set volume(n) {        this._length = Math.pow(n, 1 / 3),        this._surfaceArea = this._length * this._length * 6,        this._volume = n;    }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c08244255c74a39d828d\")",
      "url": "https://www.codewars.com/kata/speedcode-number-4-x-factory-functions-number-3-artefacts/javascript",
      "title": "SpeedCode #4 × Factory Functions #3 - Artefacts",
      "answer": "const artefact = (name, age, location, status) =>; Object.freeze({name, age, location, status});",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c08a44255c74a39d828e\")",
      "url": "https://www.codewars.com/kata/be-concise-iv-index-of-an-element-in-an-array/javascript",
      "title": "Be Concise IV - Index of an element in an array",
      "answer": "const find = (a, x) =>; (x = a.indexOf(x)) < 0 ? 'Not found' : x",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c09044255c74a39d828f\")",
      "url": "https://www.codewars.com/kata/configure-package-json-for-a-node-application/javascript",
      "title": "Configure package json for a node application",
      "answer": "const configuration = {  \"name\": \"your-pack-name\",  \"version\": \"1.2.5\"};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c09544255c74a39d8290\")",
      "url": "https://www.codewars.com/kata/coding-3min-jumping-dutch-act/javascript",
      "title": "Coding 3min : Jumping Dutch act",
      "answer": "function sc(floor) {  if (floor <= 1) return \"\";  var SCREAM = \"\";  for (let i = 0; i < floor - 1; i++) {    SCREAM += \"Aa~ \";  }  SCREAM += \"Pa!\";  if (floor <= 6) SCREAM += \" Aa!\";  return SCREAM;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c09a44255c74a39d8291\")",
      "url": "https://www.codewars.com/kata/find-the-difference-in-age-between-oldest-and-youngest-family-members/javascript",
      "title": "Find the Difference in Age between Oldest and Youngest Family Members",
      "answer": "function differenceInAges (ages) {    let max = Math.max(...ages),        min = Math.min(...ages)        diff = max - min            return [min, max, diff]}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c09f44255c74a39d8292\")",
      "url": "https://www.codewars.com/kata/blood-alcohol-content/javascript",
      "title": "Blood-Alcohol Content",
      "answer": "function bloodAlcoholContent(drinks, weight, sex, time){  return parseFloat(((drinks.ounces * drinks.abv * 5.14 / weight * (sex == 'male' ? 0.73 : 0.66)) - 0.015 * time).toFixed(4));}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0a444255c74a39d8293\")",
      "url": "https://www.codewars.com/kata/not-so-black-box/javascript",
      "title": "Not so black box",
      "answer": "//Do console.log(blackBox.toString());JSopenSesame();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0ad44255c74a39d8294\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0b544255c74a39d8295\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0be44255c74a39d8296\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0c344255c74a39d8297\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0ce44255c74a39d8298\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0d644255c74a39d8299\")",
      "url": "https://www.codewars.com/kata/unicode-total/javascript",
      "title": "Unicode Total",
      "answer": "const uniTotal = str =>; [...str].reduce((acc, char) =>; acc + char.charCodeAt(0), 0);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0df44255c74a39d829a\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0e444255c74a39d829b\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0e944255c74a39d829c\")",
      "url": "https://www.codewars.com/kata/sum-of-multiples/javascript",
      "title": "Sum of Multiples",
      "answer": "function sumMul(n,m){  if (n >;= m) return \"INVALID\";var sum = 0;  for (var i = n; i < m; i+=n) {    sum += i;  }  return sum;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0ee44255c74a39d829d\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0f744255c74a39d829e\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c0fd44255c74a39d829f\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c10444255c74a39d82a0\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c10f44255c74a39d82a1\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c11244255c74a39d82a2\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c11c44255c74a39d82a3\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c12844255c74a39d82a4\")",
      "url": "https://www.codewars.com/kata/find-the-odd-int/javascript",
      "title": "Find the odd int",
      "answer": "const findOdd = (xs) =>; xs.reduce((a, b) =>; a ^ b);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c13044255c74a39d82a5\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c13644255c74a39d82a6\")",
      "url": "https://www.codewars.com/kata/implement-a-filter-function/javascript",
      "title": "Implement a Filter function",
      "answer": "Array.prototype.filter = function(fn){  var res = [];  for (var i = 0; i<this.length; i++){    if (fn(this[i])){      res.push(this[i]);    }  }  return res;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c13b44255c74a39d82a7\")",
      "url": "https://www.codewars.com/kata/freudian-translator/javascript",
      "title": "Freudian translator ",
      "answer": "var toFreud=s=>;s.replace(/[^ ]+/g,'sex')",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c14044255c74a39d82a8\")",
      "url": "https://www.codewars.com/kata/fix-your-code-before-the-garden-dies/javascript",
      "title": "Fix your code before the garden dies! ",
      "answer": "function rainAmount(mm){  if (mm < 40)    return \"You need to give your plant \" + (40 - mm) + \"mm of water\"  return \"Your plant has had more than enough water for today!\" }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c14544255c74a39d82a9\")",
      "url": "https://www.codewars.com/kata/word-count/javascript",
      "title": "Word Count",
      "answer": "function countWords(str) {  return (str.match(/[^\\s]+/g) || []).length;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c14b44255c74a39d82aa\")",
      "url": "https://www.codewars.com/kata/no-zeros-for-heros/javascript",
      "title": "No zeros for heros",
      "answer": "function noBoringZeros(n) {  while(n%10==0 &amp;&amp; n!=0){n/=10;}  return n;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c15244255c74a39d82ab\")",
      "url": "https://www.codewars.com/kata/noobcode-01-supersize-me-dot-dot-dot-or-rather-this-integer/javascript",
      "title": "noobCode 01: SUPERSIZE ME.... or rather, this integer! ",
      "answer": "function superSize(n){  return parseInt(n.toString().split('').sort().reverse().join(''))}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c15744255c74a39d82ac\")",
      "url": "https://www.codewars.com/kata/grasshopper-function-syntax-debugging/javascript",
      "title": "Grasshopper - Function syntax debugging",
      "answer": "function main (verb, noun) {  return verb + noun}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c15b44255c74a39d82ad\")",
      "url": "https://www.codewars.com/kata/generate-user-links/javascript",
      "title": "Generate user links",
      "answer": "function generateLink(user) {  return `http://www.codewars.com/users/${encodeURIComponent(user)}`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c16144255c74a39d82ae\")",
      "url": "https://www.codewars.com/kata/triple-trouble-2/javascript",
      "title": "Triple Trouble",
      "answer": "function tripleTrouble(one, two, three) {  var result = \"\";  for (let i = 0; i < one.length; i++) {    result += one.charAt(i) + two.charAt(i) + three.charAt(i);  }  return result;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c16644255c74a39d82af\")",
      "url": "https://www.codewars.com/kata/function-3-multiplying-two-numbers/javascript",
      "title": "Function 3 - multiplying two numbers",
      "answer": "function multiply(a, b){  if(typeof a == 'number' &amp;&amp; typeof b == 'number')    return a * b;  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c16b44255c74a39d82b0\")",
      "url": "https://www.codewars.com/kata/remove-first-and-last-character-part-two/javascript",
      "title": "Remove First and Last Character Part Two",
      "answer": "function array(arr){  return arr.split(\",\").slice(1,-1).join(\" \") || null;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c16f44255c74a39d82b1\")",
      "url": "https://www.codewars.com/kata/relatively-prime-numbers/javascript",
      "title": "Relatively Prime Numbers",
      "answer": "from fractions import gcddef relatively_prime (n, l):    return [x for x in l if gcd(n, x) == 1]",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c17544255c74a39d82b2\")",
      "url": "https://www.codewars.com/kata/be-concise-iii-sum-squares/javascript",
      "title": "Be Concise III - Sum Squares",
      "answer": "let sumSquares = a =>; a.reduce((s, x) =>; s + x * x, 0)",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c17b44255c74a39d82b3\")",
      "url": "https://www.codewars.com/kata/greek-sort/javascript",
      "title": "Greek Sort",
      "answer": "def greek_comparator(lhs, rhs):    return cmp(greek_alphabet.index(lhs), greek_alphabet.index(rhs))",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c18044255c74a39d82b4\")",
      "url": "https://www.codewars.com/kata/be-concise-i-the-ternary-operator/javascript",
      "title": "Be Concise I - The Ternary Operator",
      "answer": "// TODO: Refactor and shorten the functionfunction describeAge(age) {  return \"You're a(n) \" + (age < 13 ? \"kid\" : age < 18 ? \"teenager\" : age < 65 ? \"adult\" : \"elderly\")}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c18544255c74a39d82b5\")",
      "url": "https://www.codewars.com/kata/do-something-n-dot-times-simplifying-for-loops/javascript",
      "title": "Do something \"n.times\" (Simplifying \"for\" loops)",
      "answer": "Number.prototype.times = function (f) {  for (let i = 0; i < this; ++i) {    f(i);  }};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c18d44255c74a39d82b6\")",
      "url": "https://www.codewars.com/kata/cis-122-number-1-simple-printing/javascript",
      "title": "CIS 122 #1 Simple Printing",
      "answer": "print \"Hello World!\"course = \"CIS 122\"name = \"Intro to Software Design\"print \"Welcome to \"+course+\": \"+namea = 1.1b = 3c = a + bprint \"The sum of %s and %s is %s\" % (a,b,c)x_print(\"Hello World!\")language = \"Python\"adjective = \"Fun\"x_print(\"Learning\", language, \"is\", adjective)pizzas = 10slices_per_pizza = 8total_slices = pizzas * slices_per_pizzax_print(\"There are\", total_slices, \"slices in\", pizzas, \"pizzas.\")x_print(total_slices, \": It must be dinner time!\",sep=\"\")",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c19444255c74a39d82b7\")",
      "url": "https://www.codewars.com/kata/double-char/javascript",
      "title": "Double Char",
      "answer": "const doubleChar = (str) =>; str.split(\"\").map(c =>; c + c).join(\"\");",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c19944255c74a39d82b8\")",
      "url": "https://www.codewars.com/kata/grasshopper-object-syntax-debug/javascript",
      "title": "Grasshopper - Object syntax debug",
      "answer": "var rooms = {  first: {    description: 'This is the first room',    items: {      chair: 'The old chair looks comfortable',      lamp: 'This lamp looks ancient'    }  },  second: {    description: 'This is the second room',    items: {      couch: 'This couch looks like it would hurt your back',      table: 'On the table there is an unopened bottle of water'    }  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c19d44255c74a39d82b9\")",
      "url": "https://www.codewars.com/kata/add-more-item-to-list-bug-fixes/javascript",
      "title": "Add more item to list (Bug Fixes)",
      "answer": "using System;using System.Collections.Generic;public class AddMore    {        public static List<int>; AddExtra(List<int>; listOfNumbers)        {            List<int>; finalList = new List<int>;(listOfNumbers);            finalList.Add(3);            return finalList;        }    }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1a244255c74a39d82ba\")",
      "url": "https://www.codewars.com/kata/improving-math-dot-round-x/javascript",
      "title": "Improving Math.round(x)",
      "answer": "Math.roundTo = (number, precision) =>; Number(number.toFixed(precision));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1a744255c74a39d82bb\")",
      "url": "https://www.codewars.com/kata/whats-wrong-with-these-identifiers/javascript",
      "title": "What's wrong with these identifiers?",
      "answer": "var Person = {  fistName: 'John',  lastName: 'Doe',  emailAddress: 'john.doe@email.com',  sex: 'M',};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1ac44255c74a39d82bc\")",
      "url": "https://www.codewars.com/kata/strive-matching-number-2/javascript",
      "title": "Strive Matching #2",
      "answer": "const intersect = (arra, arrb) =>; arra.filter(el =>; arrb.indexOf(el) >; -1);const matchCandidate = (job, candidate) =>; {  let equityMatches = !(candidate.desiresEquity &amp;&amp; job.equityMax === 0);  let desiredLocations = [...candidate.desiredLocations, candidate.currentLocation];  let locationMatches = intersect(job.locations, desiredLocations).length >; 0;  return equityMatches &amp;&amp; locationMatches;};const match = (job, candidates) =>; candidates.filter(matchCandidate.bind(null, job));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1b344255c74a39d82bd\")",
      "url": "https://www.codewars.com/kata/regex-count-lowercase-letters/javascript",
      "title": "Regex count lowercase letters",
      "answer": "function lowercaseCount(str){    return (str.match(/[a-z]/g) || []).length}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1b844255c74a39d82be\")",
      "url": "https://www.codewars.com/kata/a-bugs-trilogy-episode-1-let-math-dot-random-decide-your-future/javascript",
      "title": "A bugs trilogy: Episode 1 - \"Let Math.Random(); decide your future\"",
      "answer": "const yourFutureCareer = () =>; {  let career = Math.random();  return `${ career <= 0.32 ? 'FrontEnd' : (career <= 0.65 ? 'BackEnd' : 'Full-Stack') } Developer`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1bd44255c74a39d82bf\")",
      "url": "https://www.codewars.com/kata/get-the-lost-tostring-back/javascript",
      "title": "Get the lost toString back",
      "answer": "const _originalToString = func =>; Function.prototype.toString.call(func);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1c244255c74a39d82c0\")",
      "url": "https://www.codewars.com/kata/finish-guess-the-number-game/javascript",
      "title": "Finish Guess the Number Game",
      "answer": "class Guesser {  constructor(number, lives) {    this.number = number;    this.lives = lives;  }    guess(n) {    if (!this.lives) throw Error    this.lives--    return n === this.number  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1c844255c74a39d82c1\")",
      "url": "https://www.codewars.com/kata/rock-paper-scissors/javascript",
      "title": "Rock Paper Scissors!",
      "answer": "const rps = (p1, p2) =>; {  if(p1 === p2) {    return 'Draw!'  };   return `Player ${/rockscissors|scissorspaper|paperrock/.test(p1+p2)? 1 : 2} won!`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1ce44255c74a39d82c2\")",
      "url": "https://www.codewars.com/kata/drink-about/javascript",
      "title": "Drink about",
      "answer": "function peopleWithAgeDrink(age){  if(age < 14)    drink = 'toddy';  else if(age < 18)    drink = 'coke'  else if(age < 21)    drink = 'beer';  else if(age =>; 21)    drink = 'whisky';  return 'drink ' + drink;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1d444255c74a39d82c3\")",
      "url": "https://www.codewars.com/kata/how-do-i-compare-numbers/javascript",
      "title": "How do I compare numbers?",
      "answer": "def what_is(x):    if x == 42:        return 'everything'    elif x == 42 * 42:        return 'everything squared'    else:        return 'nothing'",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1db44255c74a39d82c4\")",
      "url": "https://www.codewars.com/kata/unexpected-parsing/javascript",
      "title": "Unexpected parsing",
      "answer": "function getStatus(isBusy) {  var msg = (isBusy ? \"busy\" : \"available\");  return {    status: msg  };}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1e044255c74a39d82c5\")",
      "url": "https://www.codewars.com/kata/grasshopper-terminal-game-turn-function/javascript",
      "title": "Grasshopper - Terminal Game Turn Function",
      "answer": "const doTurn = () =>; {  rollDice()  move()  combat()  getCoins()  buyHealth()  printStatus()}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1e544255c74a39d82c6\")",
      "url": "https://www.codewars.com/kata/grasshopper-bug-squashing/javascript",
      "title": "Grasshopper - Bug Squashing",
      "answer": "var health = 100var position = 0var coins = 0function main () {  rollDice()  move()  combat()  getCoins()  buyHealth()  printStatus()}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1e944255c74a39d82c7\")",
      "url": "https://www.codewars.com/kata/volume-of-a-cuboid/javascript",
      "title": "Volume of a Cuboid",
      "answer": "var Kata;Kata = (function() {  function Kata() {}  Kata.getVolumeOfCuboid = function(length, width, height) {    var l = parseFloat(length);    var w = parseFloat(width);    var h = parseFloat(height);    if(isNaN(l) || isNaN(w) || isNaN(h)) return 0;    if(l<=0 || w<=0 ||h <= 0)  return 0;        return l*w*h;  };  return Kata;})();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1ee44255c74a39d82c8\")",
      "url": "https://www.codewars.com/kata/grasshopper-variable-assignment-debug/javascript",
      "title": "Grasshopper - Variable Assignment Debug",
      "answer": "var a = \"dev\"var b = \"Lab\"var name = a + b",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1f344255c74a39d82c9\")",
      "url": "https://www.codewars.com/kata/grasshopper-order-of-operations/javascript",
      "title": "Grasshopper - Order of operations",
      "answer": "function orderOperations () {  return (2 + 2) * (2 + 2) * 2}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1f844255c74a39d82ca\")",
      "url": "https://www.codewars.com/kata/decibel-scale/javascript",
      "title": "Decibel Scale",
      "answer": "const dBScale = intensity =>; 10 * (12 + Math.log10(intensity));",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c1fd44255c74a39d82cb\")",
      "url": "https://www.codewars.com/kata/grasshopper-shopping-list/javascript",
      "title": "Grasshopper - Shopping list",
      "answer": "let [sandwiches, salads, wraps, frenchFries]  = [4, 6, 5, 10],    totalPrice = (sandwiches * 8.00) + (salads * 7.00) + (wraps * 6.50) + (frenchFries * 1.20);",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c20244255c74a39d82cc\")",
      "url": "https://www.codewars.com/kata/find-variable-which-breaks-strict-comparison/javascript",
      "title": "Find variable which breaks strict comparison!",
      "answer": "function findStrangeValue() {  return NaN;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c20744255c74a39d82cd\")",
      "url": "https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/javascript",
      "title": "Convert boolean values to strings 'Yes' or 'No'.",
      "answer": "function boolToWord( bool ){  return bool ? 'Yes':'No';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c20d44255c74a39d82ce\")",
      "url": "https://www.codewars.com/kata/wilson-primes/javascript",
      "title": "Wilson primes",
      "answer": "function amIWilson(p) {  function fact(x) {    return x <= 1 ? 1 : x * fact(x-1);  }    return (fact(p-1) + 1) / (p*p) % 1 === 0;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c21244255c74a39d82cf\")",
      "url": "https://www.codewars.com/kata/find-numbers-which-are-divisible-by-given-number/javascript",
      "title": "Find numbers which are divisible by given number",
      "answer": "function divisibleBy(numbers, divisor) {  return numbers.filter(n =>; n % divisor === 0)}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c21744255c74a39d82d0\")",
      "url": "https://www.codewars.com/kata/what-is-between/javascript",
      "title": "What is between?",
      "answer": "using System;using System.Linq; public static class Kata    {        public static int[] Between(int a, int b)        {           return Enumerable.Range(a, b - a + 1).ToArray();        }    }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c21b44255c74a39d82d1\")",
      "url": "https://www.codewars.com/kata/playing-with-cubes-ii/javascript",
      "title": "Playing with cubes II",
      "answer": "// This Cube function needs help// change the constructor so that it can take an integer for the side or no argsclass Cube {  constructor(n) {    this.side = n || 0;  }    getSide() { return this.side; }    setSide(n) {    if (!isNaN(n)) {      this.side = Math.abs(n);    }  }  };",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c22144255c74a39d82d2\")",
      "url": "https://www.codewars.com/kata/grasshopper-messi-goals/javascript",
      "title": "Grasshopper - Messi Goals",
      "answer": "var laLigaGoals = 43var championsLeagueGoals = 10var copaDelReyGoals = 5var totalGoals = laLigaGoals + championsLeagueGoals + copaDelReyGoals",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c22644255c74a39d82d3\")",
      "url": "https://www.codewars.com/kata/grasshopper-terminal-game-combat-function/javascript",
      "title": "Grasshopper - Terminal game combat function",
      "answer": "const combat = (health, damage) =>; health - damage;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c22b44255c74a39d82d4\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c23244255c74a39d82d5\")",
      "url": "https://www.codewars.com/kata/grasshopper-grade-book/javascript",
      "title": "Grasshopper - Grade book",
      "answer": "function getGrade (s1, s2, s3) {  avg = (s1+s2+s3)/3;  if (avg < 60)  return \"F\";    else if (avg < 70) return \"D\";    else if (avg < 80) return \"C\";    else if (avg < 90) return \"B\";    else return \"A\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c23844255c74a39d82d6\")",
      "url": "https://www.codewars.com/kata/invalid-login-bug-fixing-number-11/javascript",
      "title": "Invalid Login - Bug Fixing #11",
      "answer": "function validate(username, password){  var valid = new Validator();  return valid.login(username, escape(password));}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c23d44255c74a39d82d7\")",
      "url": "https://www.codewars.com/kata/a-strange-trip-to-the-market/javascript",
      "title": "A Strange Trip to the Market",
      "answer": "function isLockNessMonster(s) {  return /3\\.50|th?ree fi(?:ft|dd)y/g.test(s);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c24244255c74a39d82d8\")",
      "url": "https://www.codewars.com/kata/grasshopper-array-mean/javascript",
      "title": "Grasshopper - Array Mean",
      "answer": "const findAverage = nums =>; nums.reduce((a, b) =>; a + b) / nums.length;",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c24844255c74a39d82d9\")",
      "url": "https://www.codewars.com/kata/when-a-rose-is-not-a-rose/javascript",
      "title": "When a \"rose\" is not a \"rose\"",
      "answer": "public final class Favourites {  private Favourites() {    super();  }  public static boolean isFavourite(final String item) {    return \"rose\".equalsIgnoreCase(item.trim());  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c24d44255c74a39d82da\")",
      "url": "https://www.codewars.com/kata/unfinished-loop-bug-fixing-number-1/javascript",
      "title": "Unfinished Loop - Bug Fixing #1",
      "answer": "function createArray(number){  var newArray = [];    for(var counter = 1; counter <= number; counter++){    newArray.push(counter);  }    return newArray;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c25144255c74a39d82db\")",
      "url": "https://www.codewars.com/kata/lexical-this/javascript",
      "title": "Lexical this",
      "answer": "var Person = function(){  var person = {    _name: \"Leroy\",    _friends: [],    fillFriends(f){      this._friends.push(...f);    }  }  return person;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c25644255c74a39d82dc\")",
      "url": "https://www.codewars.com/kata/classic-hello-world/javascript",
      "title": "Classic Hello World",
      "answer": "class Solution{  static main() {    console.log(\"Hello World!\");  }  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c25b44255c74a39d82dd\")",
      "url": "https://www.codewars.com/kata/is-integer-safe-to-use/javascript",
      "title": "Is integer safe to use?",
      "answer": "function SafeInteger(n) {  return Number.isSafeInteger(n);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c26044255c74a39d82de\")",
      "url": "https://www.codewars.com/kata/are-there-any-arrows-left/javascript",
      "title": "Are there any arrows left?",
      "answer": "function anyArrows(arrows){  return arrows.some(a =>; !a.damaged);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c26544255c74a39d82df\")",
      "url": "https://www.codewars.com/kata/string-templates-bug-fixing-number-5/javascript",
      "title": "String Templates - Bug Fixing #5",
      "answer": "function buildString(...template){  return `I like ${template.join(', ')}!`;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c26a44255c74a39d82e0\")",
      "url": "https://www.codewars.com/kata/are-arrow-functions-odd/javascript",
      "title": "Are arrow functions odd?",
      "answer": "function odds(values){  return values.filter( v =>; v%2 );}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c26e44255c74a39d82e1\")",
      "url": "https://www.codewars.com/kata/take-an-arrow-to-the-knee-functionally/javascript",
      "title": "Take an Arrow to the knee, Functionally",
      "answer": "var ArrowFunc = function(arr) {  return arr.map( x =>; String.fromCharCode(x) ).join(''); }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c27544255c74a39d82e2\")",
      "url": "https://www.codewars.com/kata/add-length/javascript",
      "title": "Add Length",
      "answer": "function addLength(str){  return str.split(' ').map(function(v){return v+' '+v.length})}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c27944255c74a39d82e3\")",
      "url": "https://www.codewars.com/kata/name-shuffler/javascript",
      "title": "Name Shuffler",
      "answer": "function nameSuffle(str){  return str.split(' ').reverse().join(' ')}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c27f44255c74a39d82e4\")",
      "url": "https://www.codewars.com/kata/dollars-and-cents/javascript",
      "title": "Dollars and Cents",
      "answer": "function formatMoney(amount){  return '$' + amount.toFixed(2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c28444255c74a39d82e5\")",
      "url": "https://www.codewars.com/kata/online-rpg-player-to-qualifying-stage/javascript",
      "title": "Online RPG: player to qualifying stage?",
      "answer": "function playerRankUp (points){  return points < 100 ? false : \"Well done! You have advanced to the qualifying stage. Win 2 out of your next 3 games to rank up.\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c28844255c74a39d82e6\")",
      "url": "https://www.codewars.com/kata/simple-multiplication/javascript",
      "title": "Simple multiplication",
      "answer": "function simpleMultiplication(n) {    return n * (n % 2 ? 9 : 8);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c28d44255c74a39d82e7\")",
      "url": "https://www.codewars.com/kata/repeatit/javascript",
      "title": "repeatIt",
      "answer": "var repeatIt = function(str, n) {  return typeof str === 'string' ? Array(n+1).join(str) : 'Not a string';}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c29444255c74a39d82e8\")",
      "url": "https://www.codewars.com/kata/vowel-remover/javascript",
      "title": "Vowel remover",
      "answer": "function shortcut(string){  return string.replace(/[aeiou]/g,'')}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c29a44255c74a39d82e9\")",
      "url": "https://www.codewars.com/kata/character-frequency-2/javascript",
      "title": "Character Frequency",
      "answer": "from collections import Counterdef char_freq(message):    return Counter(message)",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c29f44255c74a39d82ea\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2a644255c74a39d82eb\")",
      "url": "https://www.codewars.com/kata/return-negative/javascript",
      "title": "Return Negative",
      "answer": "function makeNegative(num) {  return -Math.abs(num);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2ab44255c74a39d82ec\")",
      "url": "https://www.codewars.com/kata/incorrect-division-method/javascript",
      "title": "Incorrect division method",
      "answer": "def divide_numbers x, y  x.fdiv yend",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2b044255c74a39d82ed\")",
      "url": "https://www.codewars.com/kata/watermelon/javascript",
      "title": "Watermelon",
      "answer": "function divide(weight){  return weight >; 2 &amp;&amp; !(weight % 2);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2b544255c74a39d82ee\")",
      "url": "https://www.codewars.com/kata/barking-mad/javascript",
      "title": "Barking mad",
      "answer": "function Dog (breed) {  this.breed = breed;}var snoopy = new Dog(\"Beagle\");Dog.prototype.bark = function() {  return \"Woof\";};var scoobydoo = new Dog(\"Great Dane\");",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2be44255c74a39d82ef\")",
      "url": "https://www.codewars.com/kata/count-by-x/javascript",
      "title": "Count by X",
      "answer": "function countBy(x, n) {    var z = [];    for (i = 1; i <= n; i++) {        z.push(x * i);    }    return z;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2c444255c74a39d82f0\")",
      "url": "https://www.codewars.com/kata/object-oriented-piracy/javascript",
      "title": "Object Oriented Piracy ",
      "answer": "function Ship(draft,crew) { this.draft = draft; this.crew = crew;}Ship.prototype.isWorthIt = function(){return this.draft-(this.crew*1.5) >; 20;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2c944255c74a39d82f1\")",
      "url": "https://www.codewars.com/kata/enumerable-magic-number-4-true-for-none/javascript",
      "title": "Enumerable Magic #4 - True for None?",
      "answer": "function none(arr, fun){  return !arr.some(fun);}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2ce44255c74a39d82f2\")",
      "url": "https://www.codewars.com/kata/basic-subclasses-adam-and-eve/javascript",
      "title": "Basic subclasses - Adam and Eve",
      "answer": "public class God {  public static Human[] create(){    return new Human[]{new Man(), new Woman()};  }}class Human{}class Man extends Human{}class Woman extends Human{}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2d544255c74a39d82f3\")",
      "url": "https://www.codewars.com/kata/this-is-a-problem/javascript",
      "title": "\"this\" is a problem ",
      "answer": "function NameMe(first, last) {    this.firstName = first;    this.lastName  = last;    this.name = first + ' ' + last;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2da44255c74a39d82f4\")",
      "url": "https://www.codewars.com/kata/training-js-number-14-methods-of-number-object-tostring-and-tolocalestring/javascript",
      "title": "Training JS #14: Methods of Number object--toString() and toLocaleString()",
      "answer": "function colorOf(r,g,b){  r.toString(16).length < 2 ? r = '0' + r.toString(16) : r = r.toString(16);  g.toString(16).length < 2 ? g = '0' + g.toString(16) : g = g.toString(16);  b.toString(16).length < 2 ? b = '0' + b.toString(16) : b = b.toString(16);    return '#' + r + g + b;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2e144255c74a39d82f5\")",
      "url": "https://www.codewars.com/kata/are-you-playing-banjo/javascript",
      "title": "Are You Playing Banjo?",
      "answer": "function areYouPlayingBanjo(name) {  return name + (name[0].toLowerCase() == 'r' ? ' plays' : ' does not play') + \" banjo\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2e844255c74a39d82f6\")",
      "url": "https://www.codewars.com/kata/regular-ball-super-ball/javascript",
      "title": "Regular Ball Super Ball",
      "answer": "var Ball = function(ballType) {  this.ballType = ballType || 'regular';};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2ee44255c74a39d82f7\")",
      "url": "https://www.codewars.com/kata/hello-happy-codevarrior/javascript",
      "title": "Hello Happy Codevarrior!",
      "answer": "function Warrior(n){  var name = n;  this.name = function(n){    if( n ) name=n;    return name;  }  }  Warrior.prototype.toString = function(){    return \"Hi! my name's \"+this.name();}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2f444255c74a39d82f8\")",
      "url": "https://www.codewars.com/kata/color-ghost/javascript",
      "title": "Color Ghost",
      "answer": "var Ghost = function() {  this.color = [\"white\",\"yellow\",\"purple\",\"red\"][Math.floor(Math.random() * 4)];};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2f844255c74a39d82f9\")",
      "url": "https://www.codewars.com/kata/you-cant-code-under-pressure-number-2/javascript",
      "title": "You Can't Code Under Pressure #2",
      "answer": "function Counter() {  var counter = 0;    this.check = function(){return counter;};  this.increment = function(){counter++;};};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c2fe44255c74a39d82fa\")",
      "url": "https://www.codewars.com/kata/a-function-within-a-function/javascript",
      "title": "A function within a function",
      "answer": "function always(n) {  return function () { return n };  }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c30444255c74a39d82fb\")",
      "url": "https://www.codewars.com/kata/sum-without-highest-and-lowest-number/javascript",
      "title": "Sum without highest and lowest number",
      "answer": "function sumArray(array) {  if (array == null) {    return 0;  } else if (array.length < 2) {    return 0;  } else {    array = array.sort(function(a,b) {return a - b;});    var total = 0;    for (var i = 1; i < array.length - 1; i++) {      total += array[i];    }    return total;  }}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c30b44255c74a39d82fc\")",
      "url": "https://www.codewars.com/kata/sentence-smash/javascript",
      "title": "Sentence Smash",
      "answer": "smash = function (words) {  return words.join(\" \");};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c31144255c74a39d82fd\")",
      "url": "https://www.codewars.com/kata/reverse-list-order/javascript",
      "title": "Reverse List Order",
      "answer": "def reverse_list(l):  return l[::-1]",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c31744255c74a39d82fe\")",
      "url": "https://www.codewars.com/kata/name-your-python/javascript",
      "title": "Name Your Python!",
      "answer": "class Python:  def __init__(self, name):    self.name = name",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c31d44255c74a39d82ff\")",
      "url": "https://www.codewars.com/kata/grasshopper-grade-book/javascript",
      "title": "Grasshopper - Grade book",
      "answer": "function getGrade (s1, s2, s3) {  avg = (s1+s2+s3)/3;  if (avg < 60)  return \"F\";    else if (avg < 70) return \"D\";    else if (avg < 80) return \"C\";    else if (avg < 90) return \"B\";    else return \"A\";}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c32244255c74a39d8300\")",
      "url": "https://www.codewars.com/kata/cut-array-into-smaller-parts/javascript",
      "title": "Cut array into smaller parts",
      "answer": "function makeParts(arr, chunkSize) {  let newArr = [];  while (arr.length >; 0){    newArr.push(arr.splice(0, chunkSize));    }  return newArr;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c32844255c74a39d8301\")",
      "url": "https://www.codewars.com/kata/welcome-to-the-city/javascript",
      "title": "Welcome to the City",
      "answer": "function sayHello( name, city, state ) {return `Hello, ${name.join(' ')}! Welcome to ${city}, ${state}!`}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c32f44255c74a39d8302\")",
      "url": "https://www.codewars.com/kata/sleigh-authentication/javascript",
      "title": "Sleigh Authentication",
      "answer": "function Sleigh() {}Sleigh.prototype.authenticate = function(name, password) {  var _name = 'Santa Claus',      _salt = 'RudolphWithYourNoseSoBright',      _pass = '60b5b967f0752b9429bfe701b6801ce0b4524f35';  // Don't use SHA1 in production, kids!  Be on Santa's Good list and do some research...  return _name === name &amp;&amp; this.sha1(_salt+password) === _pass;};// SHA1 implementation minified from source here: http://pajhome.org.uk/crypt/md5/sha1.htmlSleigh.prototype.sha1 = function() {  function r(r) { return t(n(o(r))) }  function n(r) { return a(f(e(r), 8 * r.length)) }  function t(r) {    try {} catch (n) {      C = 0    }    for (var t, o = C ? \"0123456789ABCDEF\" : \"0123456789abcdef\", e = \"\", a = 0; a < r.length; a++) t = r.charCodeAt(a), e += o.charAt(t >;>;>; 4 &amp; 15) + o.charAt(15 &amp; t);    return e  }  function o(r) {    for (var n, t, o = \"\", e = -1; ++e < r.length;) n = r.charCodeAt(e), t = e + 1 < r.length ? r.charCodeAt(e + 1) : 0, n >;= 55296 &amp;&amp; 56319 >;= n &amp;&amp; t >;= 56320 &amp;&amp; 57343 >;= t &amp;&amp; (n = 65536 + ((1023 &amp; n) << 10) + (1023 &amp; t), e++), 127 >;= n ? o += String.fromCharCode(n) : 2047 >;= n ? o += String.fromCharCode(192 | n >;>;>; 6 &amp; 31, 128 | 63 &amp; n) : 65535 >;= n ? o += String.fromCharCode(224 | n >;>;>; 12 &amp; 15, 128 | n >;>;>; 6 &amp; 63, 128 | 63 &amp; n) : 2097151 >;= n &amp;&amp; (o += String.fromCharCode(240 | n >;>;>; 18 &amp; 7, 128 | n >;>;>; 12 &amp; 63, 128 | n >;>;>; 6 &amp; 63, 128 | 63 &amp; n));    return o  }  function e(r) {    for (var n = Array(r.length >;>; 2), t = 0; t < n.length; t++) n[t] = 0;    for (var t = 0; t < 8 * r.length; t += 8) n[t >;>; 5] |= (255 &amp; r.charCodeAt(t / 8)) << 24 - t % 32;    return n  }  function a(r) {    for (var n = \"\", t = 0; t < 32 * r.length; t += 8) n += String.fromCharCode(r[t >;>; 5] >;>;>; 24 - t % 32 &amp; 255);    return n  }  function f(r, n) {    r[n >;>; 5] |= 128 << 24 - n % 32, r[(n + 64 >;>; 9 << 4) + 15] = n;    for (var t = Array(80), o = 1732584193, e = -271733879, a = -1732584194, f = 271733878, C = -1009589776, g = 0; g < r.length; g += 16) {      for (var v = o, d = e, A = a, l = f, m = C, S = 0; 80 >; S; S++) {        t[S] = 16 >; S ? r[g + S] : i(t[S - 3] ^ t[S - 8] ^ t[S - 14] ^ t[S - 16], 1);        var y = c(c(i(o, 5), u(S, e, a, f)), c(c(C, t[S]), h(S)));        C = f, f = a, a = i(e, 30), e = o, o = y      }      o = c(o, v), e = c(e, d), a = c(a, A), f = c(f, l), C = c(C, m)    }    return Array(o, e, a, f, C)  }  function u(r, n, t, o) { return 20 >; r ? n &amp; t | ~n &amp; o : 40 >; r ? n ^ t ^ o : 60 >; r ? n &amp; t | n &amp; o | t &amp; o : n ^ t ^ o }  function h(r) { return 20 >; r ? 1518500249 : 40 >; r ? 1859775393 : 60 >; r ? -1894007588 : -899497514 }  function c(r, n) {    var t = (65535 &amp; r) + (65535 &amp; n),      o = (r >;>; 16) + (n >;>; 16) + (t >;>; 16);    return o << 16 | 65535 &amp; t  }  function i(r, n) { return r << n | r >;>;>; 32 - n }  var C = 0;  return r}();",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c33444255c74a39d8303\")",
      "url": "https://www.codewars.com/kata/max-headroom-and-javascript-style/javascript",
      "title": "Max Headroom and JavaScript style",
      "answer": "function getMax1(){  var max = {name: 'Max Headroom'}  return max;}function getMax2(){// Have your return object on same linereturn {name: 'Max Headroom'};}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c33944255c74a39d8304\")",
      "url": "https://www.codewars.com/kata/yield-to-the-block/javascript",
      "title": "Yield to the Block",
      "answer": "def compute  block_given? ? yield : \"Do not compute\" end",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c34144255c74a39d8305\")",
      "url": "https://www.codewars.com/kata/kata-example-twist/javascript",
      "title": "Kata Example Twist",
      "answer": "var websites = [];while (websites.length < 1000) websites.push(\"codewars\")",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c34644255c74a39d8306\")",
      "url": "https://www.codewars.com/kata/broken-counter/javascript",
      "title": "Broken Counter",
      "answer": "function Counter() {  this.value = 0;}Counter.prototype.increase = function() {  this.value++;};Counter.prototype.getValue = function() {  return this.value;};Counter.prototype.reset = function() {  this.value = 0;};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c34c44255c74a39d8307\")",
      "url": "https://www.codewars.com/kata/function-1-hello-world/javascript",
      "title": "Function 1 - hello world",
      "answer": "function greet() {    return \"hello world!\";    }",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c35144255c74a39d8308\")",
      "url": "https://www.codewars.com/kata/function-2-squaring-an-argument/javascript",
      "title": "Function 2 - squaring an argument",
      "answer": "// Write the \"square\"-function herevar square = function(a){  return a*a;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c35844255c74a39d8309\")",
      "url": "https://www.codewars.com/kata/semi-optional/javascript",
      "title": "Semi-Optional",
      "answer": "function wrap(value) {  return  {    \"value\":value   };}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c35d44255c74a39d830a\")",
      "url": "https://www.codewars.com/kata/return-to-sanity/javascript",
      "title": "Return to Sanity",
      "answer": "function mystery() {  var results =    {sanity: 'Hello'};  return results;}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c36344255c74a39d830b\")",
      "url": "https://www.codewars.com/kata/basic-training-add-item-to-an-array/javascript",
      "title": "Basic Training: Add item to an Array",
      "answer": "// add the value \"codewars\" to the already defined websites arraywebsites.push('codewars')",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c36844255c74a39d830c\")",
      "url": "https://www.codewars.com/kata/get-planet-name-by-id/javascript",
      "title": "Get Planet Name By ID",
      "answer": "function getPlanetName(id){  var names = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptun'];  return names[id - 1];}",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c36e44255c74a39d830d\")",
      "url": "https://www.codewars.com/kata/shifty-closures/javascript",
      "title": "Shifty Closures",
      "answer": "var name;function greet_abe() {  name = 'Abe';  return \"Hello, \" + name + '!';};function greet_ben() {  name = 'Ben';   return \"Hello, \" + name + '!';};",
      "newQuestion": true,
      "__v": 0
   },
   {
      "_id": "ObjectId(\"58c0c37444255c74a39d830e\")",
      "url": "https://www.codewars.com/kata/mr-freeze/javascript",
      "title": "Mr. Freeze",
      "answer": "Object.freeze(MrFreeze)",
      "newQuestion": true,
      "__v": 0
   }
]
