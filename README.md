# Coding Bootcamp JavaScript (JS)

Our Coding bootcamp javascript 2020

## Members of our Bootcamp

88 members (Mostly from India and canada)

## Questions

**Question:** How to find max and min number in an array using reduce method ?

----------

**Question:** Try to fill in the blanks. (Without any changes)
You can add some codes instead of ?????????.
Answer: The output must be true.

```js
const x = ?????????;
console.log(x == 5 && x == 25 && x == 125); // true
```

Note: Please not search and google it.
No time limit, anyone can think and try for this.

----------

Concept: Consider the two functions below. Will they both return the same thing? Why and not?

```js
function t1()
{
  return {
      bar: "hello"
  };
}
function t2()
{
  return
  {
      bar: "hello"
  };
}
```

Test:

```js
console.log("t1:");
console.log(t1());
console.log("t2:");
console.log(t2());
```

----------

Are you familiar with data type and operators?
If you think you are a js expert, think about this:

**Question:** What will the code below output? Explain your answer. (guess the output)

```js
console.log(0.1 + 0.2);
console.log(0.1 + 0.2 == 0.3);
```

----------

**Question:** Write a add method which will work properly when invoked using either syntax below.

```js
console.log( add(2)(3) );  // Outputs: 5
console.log( add(4)(6) );  // Outputs: 10
console.log( add(6)(6) );  // Outputs: 12
```

------------

Okay, we go to next step:

**Question:** Write a add method which will work properly when invoked using either syntax below.

```js
console.log( add(0) );  // Outputs: 0
console.log( add(2) );  // Outputs: 2
console.log( add(6) );  // Outputs: 6
console.log( add(2)(3) );  // Outputs: 5
console.log( add(4)(6) );  // Outputs: 10
console.log( add(6)(6) );  // Outputs: 12
```

-------

But we have to expert in it to be sure of them. So trying... 👍

What about this?
var cause a different in this case or no?

```js
const myNumber = '3';
(function (callback) {
  console.log(myNumber);
  var myText = 'hello';
  callback();
})(function () {
    console.log(myNumber);
    console.log(myText);
  })
```

--------

So it will be interest at now:

```js
const myNumber = '3';
(function (callback) {
  console.log(myNumber);
  myText = 'hello';
  callback();
})(function () {
    console.log(myNumber);
    console.log(myText);
  })
```

Guess it.

----------

**Question:** What will the following code output and why?

```js
var b = 1;
function outer(){
    var b = 2
    function inner(){
        b++;
        let b = 5;
        console.log(b)
    }
    inner();
}
outer();
```

------------

**Question:** What will the following code output and why?

```js
var b = 1;
function outer(){
     var b = 2
    function inner(){
        b++;
        var b = 5;
        console.log(b)
    }
    inner();
}
outer();
```

----------

**Question:** Guess output

```js
console.log(color);
const color = '#aaa';
```

----------

**Question:** Guess output

```js
console.log(color);
var color = '#aaa';
```

----------

**Question:** Guess output

```js
console.log(color);
let color = '#aaa';
```

----------

**Question:** Guess output

```js
function square(a = 4) {
  return a * a;
}
console.log( square() );
```

----------


**Question:** Guess output

```js
var a=4;
function square(a = a) {
  return a * a;
}
console.log( square() );
console.log( square(2) );
```

----------


**Question:** Guess output

```js
let a=4;
function square(a = a) {
  return a * a;
}
console.log( square() );
console.log( square(2) );
```

----------


**Question:** Guess output

```js
const a=4;
function square(a = a) {
  return a * a;
}
console.log( square() );
console.log( square(2) );
```

----------

Question:

```js
function test(someVal) {
  typeof variable; // first question
  if (someVal) {
    typeof variable; // second question
    let variable;
  }
}
test(true);
```

----------


**Question:** What will the code below output to the console and why?


```js
(function(){
  var a = b = 3;
})();
console.log("a defined? " + (typeof a !== 'undefined'));
console.log("b defined? " + (typeof b !== 'undefined'));
```

----------

**Question:** What will the code below output to the console and why?

```js
var myObject = {
    foo: "bar",
    func: function() {
        var self = this;
        console.log("outer func:  this.foo = " + this.foo);
        console.log("outer func:  self.foo = " + self.foo);
        (function() {
            console.log("inner func:  this.foo = " + this.foo);
            console.log("inner func:  self.foo = " + self.foo);
        }());
    }
};
myObject.func();
```

----------

**Question:** In what order will the numbers 1-4 be logged to the console when the code below is executed? Why?
Guess order and why?


```js
(function() {
    console.log(1); 
    setTimeout(function(){console.log(2)}, 1000); 
    setTimeout(function(){console.log(3)}, 0); 
    console.log(4);
})();
```

----------

**Question:** Tell output of variables:

```js
var a = b = 3;
```

----------

What's Palindrome?
A palindrome is a word, number, phrase, or other sequence of characters which reads the same backward as forward, such as madam, racecar. There are also numeric palindromes, including date/time stamps using short digits 11/11/11 11:11 and long digits 02/02/2020. 

**Question:** Write a simple function that returns a boolean indicating whether or not a string is a palindrome.

Test case:
— level => true
— levels => false

----------

**Question:** guess the `d` value

```js
var d = {};
[ 'zebra', 'horse' ].forEach(function(k) {
  d[k] = undefined;
});
console.log (d)
```

----------

**Question:** What will the code below output to the console and why ?


```js
console.log(1 +  "2" + "2");
```

----------


**Question:** What will the code below output to the console and why ?

```js
console.log(1 +  +"2" + "2");
```

----------

**Question:** What will the code below output to the console and why ?


```js
console.log(1 +  -"1" + "2");
```

----------

**Question:** What will the code below output to the console and why ?


```js
console.log(+"1" +  "1" + "2");
```

----------

**Question:** What will the code below output to the console and why ?


```js
console.log( "A" - "B" + "2");
```

----------

**Question:** What will the code below output to the console and why ?


```js
console.log( "A" - "B" + 2);
```

----------


**Question:** What will be the output of the following code:


```js
for (var i = 0; i < 5; i++) {
  setTimeout(function() { console.log(i); }, i * 1000 );
}
```

----------


**Question:** What is the output out of the following code? Explain your answer.

```js
var a={},
    b={key:'b'},
    c={key:'c'};
a[b]=123;
a[c]=456;
console.log(a[b]);
```

----------

**Question:** guess output

```js
console.log( + "***" );
```

----------

**Question:** guess output

```js
console.log(- "***" );
```

----------

**Question:** guess output

```js
console.log( new Number(5) == 5);
console.log( new Number(5) == 5 == "5");
console.log( new Number(5) == 5 == "5" == new Number(6));
```

----------

**Question:** guess output

```js
console.log( new Number(5) === 5);
```

----------

**Question:** guess output

```js
class test {
   #age=45;
}
g=new test();
g.age
```

----------

**Question:** guess output

```js
#age=45;
```

----------

**Question:** JavaScript is an OOP scripting language? or no?

----------

**Question:** guess output

```js
p=new Point();
console.log(p);// first answer

p=new Point(4);// second answer
console.log(p);// third answer
console.log(p.toString()); //forth answer
```

----------

**Question:** guess output

```js
0.1 + "0.2"
"0.1" + 0.2
```

--------

## Members of our Bootcamp

- Surya
- Max Base
- Prajwal
- prashant gupta
- Kalyan
- Shubham Ganguly
- Bhavik Chavda
- mooo
- Jayakumar
- Rishabh Kumar
- Utkarsh Malik (Super)
- DJANGO
- Vishal Singh
- Aswanidutt Addaguduru
- V
- Akhil Joshi
- Gimmy
- Mohit
- Siddharth
- Naman Bhandari
- Nithish
- Khalpada Shyamal
- Deep
- Anand kumar
- Prathmesh
- Yugesh
- Vijay Kumar
- Pankaj Tanwar
- Dhruv
- Harsh
- Shivan Sahni
- B K
- Aniruddh
- Jay Parmar
- Raunaq
- Keerthan S
- lucifer
- International khiladi
- Nipun
- Dan
- Ayush Singh
- Ashwin Menon
- Snehashis
- Henny
- Saurab
- Droyder
- Vinit Raut
- Rohan Arihant
- Nitn Bagoriya
- Aaquib
- Ayush
- Praveen Kumar
- vvp
- gag
- Chetan Kharat
- Dfg
- Fubuki Shirou
- Rajeev Sharma
- Ritesh Mukim CSE'17
- Arjun
- suhan
- Sohail Akhtar
- Ravi
- Gaurav
- Ayush
- jain sanchit
- Mrinmay
- Hrinal Bunkar
- Subham
- Nitin CHAURASIA
- Pranjal Kandhari
- Ankit Sharma
- Ebrahimi
- Ayush
- A
- and more...
