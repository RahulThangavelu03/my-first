# my-<!DOCTYPE html>
<html>
<body>

<h2>h1</h2>
<p>p1</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 45+ 6986;
</script>

</body>
</html> 
<!DOCTYPE html>
<html>
<body>

<h2>h1</h2>
<p>p1.</p>

<script>
alert(5 + 6);
</script>
</body>
</html> 

<!DOCTYPE html>
<html>
<body>

<h2>h</h2>

<p>p1</p>

<p id="demo"></p>

<script>
 x = F1(1, 1);
document.getElementById("demo").innerHTML = x;

function F1(a, b)
  {
  return a * b;
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>h1</h2>

<p>p1</p>

<p>p2</p>

<p id="demo"></p>

<script>
const person = 
  {
  firstName: "John",
  lastName : "Doe",
  id     :  5566
};

document.getElementById("demo").innerHTML =
person.firstName + " " + person.lastName;
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>h1</h2>

<p>p1</p>

<p id="demo"></p>

<script>
const person =
  {
  firstName: "John",
  lastName : "Doe",
  id     : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};


document.getElementById("demo").innerHTML = person.fullName;
</script>

</body>
</html>

<!DOCTYPE html>
<html>
 <body>
  <h1> h</h1>
  <p1>P</p1>
  <p id=demo></p>
  <script>
    var x = myfunction(1,2);
   document.getElementbyId("demo")inner.HTMl= x;
   function myfunction (a,b)
   {
   return a *b ;
   }
   </script>
 </body>
 </html>
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo1"></p>

<p id="demo2"></p>

<script>
myFunction();

function myFunction() {
  let carName = "BMW";
  document.getElementById("demo1").innerHTML =
  typeof carName + " " + carName;
}

document.getElementById("demo2").innerHTML =
typeof carName;
</script>

</body>
</html>

<!DOCTYPE HTML>
<html>
<body>
 <h1>h</h1>

<p id ="demo"></p>

 <script>
  const car= { company:"audi", model:"q3",color : "white"};
  document,getElementById("demo).innerHTML = the car name is " + car.name;
 </script>
 
 </body>
 </html>
  
  

 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript Objects</h2>

<p id="demo"></p>

<script>
const car = {type:"Fiat", model:"500", color:"white"};
document.getElementById("demo").innerHTML = "The car type is " + car.type;
</script>

</body>
</html>

  

<!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>P</p>
<p id="demo"></p>

<script>
 
let text = "nfenfnefnn";
document.getElementById("demo").innerHTML = text.length;
 
 </script>

</body>
</html>

<! DOCTYPE HTML>
<HTML>
 <body>
  
  <h1>ff</h1>
  <p>fkff</p>
  <p id= "demo"></p>
  
  <script>
   let str = "mnfujenjn";
   document.grtelementById("demo").innerHTML= str.slice(1,5);
  </script>
  
 </body>
 </html>
 
 
<!DOCTYPE html>
<html>
<body>

<h3>h</h3>

<p>p</p>
<p id="demo"></p>

<script>

 let str = "uhfjfnueenfi;
document.getElementById("demo").innerHTML = str.slice(-6,-2);
</script>

</body>
</html>

<!DOCTYPE HTML>
<html>
 <body>
  <h1>h</h1>
   <p1>P</p1>
  <p id="demo"></p>
  
  <script>
   let str = "hfhjfhefuhefui";
   document.getelementById("demo").innerHTML= str.substring(7,9);
  </script>
 
 </body>
 </html>

<!DOCTYPE html>
<html>
<body>

<h2>h</h2>

<p>P</p>

<button onclick="myFunction()">Try it</button>
<p id="demo">P2</p>

 <script>
function myFunction() {
  let text = document.getElementById("demo").innerHTML; 
  document.getElementById("demo").innerHTML = text.replace("kdmmddiiij","Wdjuhfnfjd");
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>P</p>
<button onclick="myFunction()">Try it</button>
<p id="demo">Hello World!</p>

<script>
function myFunction() {
  let text = document.getElementById("demo").innerHTML;
  document.getElementById("demo").innerHTML = text.toUpperCase();
}
</script>

</body>
</html>

<!DOCTYPE HTML>
<html>
 <body>
  <h1>h</h1>
  <p id = "demo">HELlo </p>
  <button onclick = myfunction()></button>
  
  <script>
   function myfunction()
   {
   let text = document.getElementById("demo").innerHtml;
   document.getElementById("demo").innerHTMl()= text .toUpperCase();
  </script>
  
 </body>
 </html>
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p>

<p id="demo"></p>

<script>
let text = "Hello";
const myArr = text.split("");

text = "";
for (let i = 0; i < myArr.length; i++) 
                                 {
  text += myArr[i] + "<br>"
}
document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo"></p>

<script>
let str = "Please locate where 'locate' occurs!";
document.getElementById("demo").innerHTML = str.indexOf("locate");
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>P</h2>

<p>P</p>

<p id="demo"></p>

<script>
let str = "Please locate where 'locate' occurs!";
document.getElementById("demo").innerHTML = str.lastIndexOf("locate");
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo"></p>

<script>
let text = "The rain in SPAIN stays mainly in the plain"; 
document.getElementById("demo").innerHTML = text.match(/ain/g);
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2> 
<h2>H</h2>
<p>P</p>

<p id="demo"></p>

<script>
const fruits = ["banana", "orange", "apple", "mango"];
document.getElementById("demo").innerHTML = fruits.toString();
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>J</h2>
<h2>P</h2>
<p>P</p>

<p id="demo1"></p>
<p id="demo2"></p>

<script>
const fruits = ["banana", "orange", "apple", "mango"];
document.getElementById("demo1").innerHTML = fruits;
fruits.pop();
document.getElementById("demo2").innerHTML = fruits;
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>J</h2> 
<h2>p</h2>
<p>P</p>

<button onclick="myFunction()">Try it</button>
<p id="demo"></p>

<script>
const fruits = ["banana", "orange", "apple", "mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction()
 {
  fruits.push("grape");
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2> 
<h2>H</h2>
<p>P</p>

<p id="demo1"></p>
<p id="demo2"></p>
<p id="demo3"></p>

<script>
const fruits = ["Banana", "orange", "apple", "mango"];
document.getElementById("demo1").innerHTML = fruits;
document.getElementById("demo2").innerHTML = fruits.shift();
document.getElementById("demo3").innerHTML = fruits;
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2> 
<h2>H</h2>
<p>P</p>

<button onclick="myFunction()">Try it</button>
<p id="demo"></p>

<script>
const fruits = ["Banana", "orange", "apple", "mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction() 
 {
  fruits.unshift("Lemon");
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>p</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
const fruits = ["Banana", "orange", "apple", "mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction()
 {
  fruits.sort();
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>h</h2>

<p>p</p>
<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>

const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction()
 {
   fruits.sort();
  fruits.reverse();
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>p</p>

<button onclick="myFunction()">Try it</button>
<p id="demo"></p>

<script>
const points = [40, 100, 1, 5, 25, 10];
document.getElementById("demo").innerHTML = points;

function myFunction() 
 {
  points.sort(function(a, b){return b - a});
  document.getElementById("demo").innerHTML = points;
}
</script>

</body>
</html>


<!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>p</p>

<script>
const points = [40, 100, 1, 5, 25, 10];
document.getElementById("demo").innerHTML = myArrayMax(points);

function myArrayMax(arr)
 {
  return Math.max.apply(null, arr);
}
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>h</h2>
<p>p.</p>

<script>
const points = [40, 100, 1, 5, 25, 10];
document.getElementById("demo").innerHTML = myArrayMin(points);

function myArrayMin(arr)
 {
  let len = arr.length;
  let min = Infinity;
  while (len--) {
    if (arr[len] < min) {
      min = arr[len];
    }
  }
  return min;
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo">Good Evening!</p>

<script>
if (new Date().getHours() < 18) {
  document.getElementById("demo").innerHTML = "Morning";
}
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo"></p>

<script>
const hour = new Date().getHours(); 
let greeting;

if (hour < 18) {
  greeting = " Morning";
} else {
  greeting =" evening";
}

document.getElementById("demo").innerHTML = greeting;
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript switch</h2>

<p id="demo"></p>

<script>
let day;
switch (new Date().getDay()) {
  case 0:
    day = "S";
    break;
  case 1:
    day = "M";
    break;
  case 2:
    day = "T";
    break;
  case 3:
    day = "W";
    break;
  case 4:
    day = "T";
    break;
  case 5:
    day = "F";
    break;
  case  6:
    day = "S";
}
document.getElementById("demo").innerHTML = 
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p id="demo"></p>

<script>
const cars = ["audi", "Volvo", "BMW", "KIA"];
let i, len, text;
for (i = 0, len = cars.length, text = ""; i < len; i++) {
  text += cars[i] + "<br>";
}
document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p>
<p id="demo"></p>

<script>

const person = {
  firstName: "raj",
  lastName: "kumar",
  id: 1000,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};

document.getElementById("demo").innerHTML = person.fullName();
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript Class Method</h2>

<p>How to define and use a Class method.</p>

<p id="demo"></p>

<script>
class Car {
  constructor(name, year) {
    this.name = name;
    this.year = year;

  }
  age() {
    let date = new Date();
    return date.getFullYear() - this.year;
  }
}

let myCar = new Car("Ford", 2014);
document.getElementById("demo").innerHTML =
"My car is " + myCar.age() + " years old.";
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
class Car 
 {
  constructor(name, year)
 {
    this.name = name;
    this.year = year;
 }
  age()
 {
    let date = new Date();
    return date.getFullYear() - this.year;
  }
 }

let myCar = new Car("Ford", 2014);
document.getElementById("demo").innerHTML =
"My car is " + myCar.age() + " years old.";
</script>

</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p id="demo"></p>

<script>
var x = myFunction(4, 3);
document.getElementById("demo").innerHTML = x;

function myFunction(a, b) {
  return a * b;
}
</script>

</body>
</html>

 
 
<!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
function findMax() {
  let max = -Infinity;
  for(let i = 0; i < arguments.length; i++)
    {
    if (arguments[i] > max) 
 {
      max = arguments[i];
    }
  }
  return max;
} 
document.getElementById("demo").innerHTML = findMax(4, 5, 6);
</script>

</body>
</html>



 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
let x = myFunction();
function myFunction() 
 {
  return this;
}
document.getElementById("demo").innerHTML = x; 
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p> 

<p id="demo"></p>

<script>
const myObject = 
 {
  firstName:"John",
  lastName: "Doe",
  fullName: function() 
 {
    return this.firstName + " " + this.lastName;
  }
}
document.getElementById("demo").innerHTML = myObject.fullName();
</script>

</body>
</html>


<!DOCTYPE html>
<html>
<body>

<h1 id="id01">h</h1>

<script>
const element = document.getElementById("id01");
element.innerHTML = "New Heading";
</script>

<p>JavaScript changed "Old Heading" to "New Heading".</p>

</body>
</html> 

 
 <!DOCTYPE html>
<html>
<head>
<script>
function validateForm() 
 {
  let x = document.forms["myForm"]["fname"].value;
  if (x == "") {
    alert("Name must be filled out");
    return false;
  }
}
</script>

 </head>
<body>

<h2>h</h2>

<form name="myForm" action="/action_page.php" onsubmit="return validateForm()" method="post">
  Name: <input type="text" name="fname">
  <input type="submit" value="Submit">
</form>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p>


<p id="p1">Hello World!</p>
<p id="p2">Hello World!</p>

<script>
document.getElementById("p2").style.color = "green";
document.getElementById("p2").style.fontFamily = "Arial";
document.getElementById("p2").style.fontSize = "larger";
</script>


</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<button id="myBtn">Try it</button>

<script>
document.getElementById("myBtn").addEventListener("click", myFunction);

function myFunction()
 {
  alert ("Hello World!");
}
</script>

</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<body>

<h2>h</h2> 

<p id="demo"></p>

<script>
const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits.toString();
</script>

</body>
</html>

 
 
<!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
const fruits = [  "Apple","Orange" "Mango"];
let fLen = fruits.length;

let text = "<ul>";
for (let i = 0; i < fLen; i++)
 {
  text += "<li>" + fruits[i] + "</li>";
}
text += "</ul>";

document.getElementById("demo").innerHTML = fruits;
</script>

</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<body>
<h3>h</h3>
 <p id="demo1"></p>
<p id="demo2"></p>

<script>
const fruit=["apple",  "Apple", "Mango"];
document.getElementById("demo1").innerHTML = fruits;
fruits.pop();
document.getElementById("demo2").innerHTML = fruits;
</script>

</body>
</html>

 
 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

 <button onclick="myFunction()">Try it</button>
<p id="demo"></p>

<script>
const fruits = [ "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction() 
 {
  fruits.push("Orange");
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
 <p>P</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
const fruits = [ "Apple","Orange", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction() {
  fruits.sort();
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
let answer1 = "dddf";
let answer2 = "fdfgd'";
 
document.getElementById("demo").innerHTML = answer1 + "<br>" + answer2 ; 
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
let text = "Akfnfeioe";
document.getElementById("demo").innerHTML = text.length;
</script>

</body>
</html>


<!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
let str = "Apple, Banana, ;
document.getElementById("demo").innerHTML = str.slice(4,8); 
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript String Methods</h2>

<p id="demo"></p>

<script>
let str = "i like this!";
document.getElementById("demo").innerHTML = str.search("like);
</script>

</body>
</html>



<!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p id="p1">HW</p>

<script>
document.getElementById("p1").innerHTML = "hello world ";
</script>

 </body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>
<input id="numb">
<button type="button" onclick="myFunction()">Submit</button>
<p id="demo"></p>

<script>
function myFunction()
 {
  let x = document.getElementById("numb").value;
  let text;
  if (isNaN(x) || x < 1 || x > 10) 
 {
    text = "valid input";
  } else 
 {
    text = "invalid input";
  }
  document.getElementById("demo").innerHTML = text;
}
</script>

</body>
</html> 

<!DOCTYPE html>
<html>
<body>
<h1 id="id1">this is a Heading 1</h1>

<button type="button" onclick="document.getElementById('id1').style.color = 'yellow'"> Click this</button>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript HTML Events</h2>
<h2 onclick="this.innerHTML='the text changed'">Click on this </h2>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 
"Page hostname is: " + window.location.hostname;
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML =
"Page path is: " + window.location.pathname;
</script>

</body>
</html>

 <html>
<head>

 <script>
function goBack()
 {
  window.history.back()
}
</script>
 
</head>
<body>

<input type="button" value="Back" onclick="goBack()">

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML =
"navigator.cookieEnabled is " + navigator.cookieEnabled;
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Timing</h2>

<p>Click "Try it". Wait 3 seconds, and the page will alert "Hello".</p>

<button onclick="setTimeout(myFunction, 5000);">Try it</button>

<script>
function myFunction() {
  alert('Hello');
}
</script>

</body>
</html>
<head>  
<title> SignUp Page</title>  
</head>  
<body> 
<h1> Create acc</h1>  
<table>
<tr><td> Name</td>   
<td><input type="text" placeholder="Enter your name" id="n1"></td></tr>  
<tr><td>Email </td>  
<td><input type="text" placeholder="Enter your email id" id="e1"></td></tr>  
<tr><td> Set Password</td>  
<td><input type="password" placeholder="Set a password" id="p1"></td></tr>  
<tr><td>Confirm Password</td>  
<td><input type="password" placeholder="Confirm your password" id="p2"></td></tr>  
<tr><td>  
<input type="submit" value="Create" onClick="create_account()"/>  
</table>  
<script>  
function create_account()
 {  
var n=document.getElementById("n1").value;  
var e=document.getElementById("e1").value;  
var p=document.getElementById("p1").value;  
var cp=document.getElementById("p2").value;  

        var letters = /^[A-Za-z]+$/;  
        var email_val = /^([a-zA-Z0-9_\.\-])+\@(([a-zA-Z0-9\-])+\.)+([a-zA-Z0-9]{2,4})+$/;  

if(n==''||e==''||p==''||cp=='')
 {  
alert("Enter each details correctly");  
}  
else if(!letters.test(n))  
        {  
            alert('Name is incorrect must contain alphabets only');  
        }  
else if (!email_val.test(e))  
        {  
            alert('Invalid email format please enter valid email id');  
        }  
else if(p!=cp)  
{  
alert("Passwords not matching");  
}  
else if(document.getElementById("p1").value.length > 12)  
{  
alert("Password maximum length is 12");  
}  
else if(document.getElementById("p1").value.length < 6)  
{  
alert("Password minimum length is 6");  
}  
else{  
alert(" account created);   
}  
}  
</script>  
</body>  
</html>  
 
 
 <!DOCTYPE html>
<html>
<body>
<h2>H</h2>
<p>P</p>
<p id="demo1"></p>
<p id="demo2"></p>
 
<script>
const fruits = [  "Apple", "Mango","orange"];
document.getElementById("demo1").innerHTML = fruits;
fruits.pop();
document.getElementById("demo2").innerHTML = fruits;
</script>

</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2> 
<h2>push()</h2>
<p>The push() method appends a new element to an array.</p>

<button onclick="myFunction()">Try it</button>
<p id="demo"></p>

<script>
const fruits = [  "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction() 
 {
  fruits.push("orange");
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2> 
<p id="demo1"></p>
<p id="demo2"></p>

<script>
const fruits = [ "Orange", "Apple", "Mango"];
document.getElementById("demo1").innerHTML = fruits;
fruits.shift();
document.getElementById("demo2").innerHTML = fruits;
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p>
<button onclick="myFunction()">Try it</button>
<p id="demo"></p>

 <script>
const fruits = [ "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction()
 {
    fruits.sort();
  fruits.reverse();
  document.getElementById("demo").innerHTML = fruits;
}
</script>

</body>
</html>

 nclick="this.innerHTML='the text changed'">Click on this </h2>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 
"Page hostname is: " + window.location.hostname;
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML =
"Page path is: " + window.location.pathname;
</script>

</body>
</html>

 <html>
<head>

 <script>
function goBack()
 {
  window.history.back()
}
</script>
 
</head>
<body>

<input type="button" value="Back" onclick="goBack()">

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p>P</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML =
"navigator.cookieEnabled is " + navigator.cookieEnabled;
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>

<p id="p1">HW</p>

<script>
document.getElementById("p1").innerHTML = "hello world ";
</script>

 </body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p>P</p>
<input id="numb">
<button type="button" onclick="myFunction()">Submit</button>
<p id="demo"></p>

<script>
function myFunction()
 {
  let x = document.getElementById("numb").value;
  let text;
  if (isNaN(x) || x < 1 || x > 10) 
 {
    text = "valid input";
  } else 
 {
    text = "invalid input";
  }
  document.getElementById("demo").innerHTML = text;
}
</script>

</body>
</html> 

<!DOCTYPE html>
<html>
<body>
<h1 id="id1">this is a Heading 1</h1>

<button type="button" onclick="document.getElementById('id1').style.color = 'yellow'"> Click this</button>
</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>JavaScript HTML Events</h2>
<h2 onclick="this.innerHTML='the text changed'">Click on this </h2>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<body>

<h2>H</h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 
"Page hostname is: " + window.location.hostname;
</script>

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">
 
<p>P</p>
<p>Name : <input type="text" ng-model="name" placeholder="Enter name here"></p>
<h1>Hello {{name}}</h1>

</div>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">
<p> sum {{ 1 + 2 }}</p>
</div>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<p>Try to change the names.</p>

<div ng-app="myApp" ng-controller="myCtrl">

First Name: <input type="text" ng-model="firstName"><br>
Last Name: <input type="text" ng-model="lastName"><br>
<br>
Full Name: {{firstName + " " + lastName}}

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
    $scope.firstName= "A";
    $scope.lastName= "B";
});
</script>

</body>
</html>

 
<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" my-directive></div>

<script>
var app = angular.module("myApp", []);
app.directive("myDirective", function() {
    return {
        template : "I was made in a directive constructor!"
    };
});
</script>

</body>
</html>


 <!DOCTYPE html>
<html>
<body>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>

<div ng-app="myApp" ng-controller="myCtrl">
{{ firstName + " " + lastName }}
</div>

<script>
var app = angular.module("myApp", []);
app.controller("myCtrl", function($scope) {
    $scope.firstName = "John";
    $scope.lastName = "Doe";
});
</script>

<p>body para.</p>

</body>
</html>
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<form ng-app="" name="myForm">
    Email:
    <input type="email" name="myAddress" ng-model="text">
    <span ng-show="myForm.myAddress.$error.email">Not a valid e-mail address</span>
</form>

<p>P</p>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<form ng-app="" name="myForm" ng-init="myText = 'post@myweb.com'">

Email:
<input type="email" name="myAddress" ng-model="myText" required>
<p>Edit the e-mail address, and try to change the status.</p>
<h1>h</h1>
<p>Valid: {{myForm.myAddress.$valid}} </p>
<p>Dirty: {{myForm.myAddress.$dirty}} </p>
<p>Touched: {{myForm.myAddress.$touched}} </p>

</form>

</body>
</html>

 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">
    <p ng-bind="firstname"></p>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.firstname = "A";
    $scope.lastname = "B";    
});
</script>

<p>P</p>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">
    <h1 ng-click="changeName()">{{firstname}}</h1>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.firstname = "A";
    $scope.changeName = function() {
        $scope.firstname = "B";
    }
});
</script>

<p>P.</p>

</body>
</html>

 
 
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

First Name: <input type="text" ng-model="firstName"><br>
Last Name: <input type="text" ng-model="lastName"><br>
<br>
Full Name: {{firstName + " " + lastName}}

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.firstName = "a";
    $scope.lastName = "b";
});
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">
    <p>First name: {{firstname}}</p>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
    $scope.firstname = "John";
    $scope.lastname = "Doe";    
});
</script>

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

First Name: <input type="text" ng-model="firstName"><br>
Last Name: <input type="text" ng-model="lastName"><br>
<br>
Full Name: {{firstName + " " + lastName}}

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.firstName = "A";
    $scope.lastName = "B";
});
</script>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<h1>{{carname}}</h1>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) 
 {
    $scope.carname = "Volvo";
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<input ng-model="name">

<h1>My name is {{name}}</h1>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) 
 {
    $scope.name = "John Doe";
});
</script>

<p>P</p>

</body>
</html>

<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<ul>
  <li ng-repeat="x in names">{{x}}</li>
</ul>

</div>

<script>
var app = angular.module('myApp', []);

app.controller('myCtrl', function($scope) 
 {
    $scope.names = ["Emil", "Tobias", "Linus"];
});
</script>

<p>P.</p>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body ng-app="myApp">

<p>P1</p>
<h1>{{color}}</h1>

<div ng-controller="myCtrl">

<p>P2</p>
<h1>{{color}}</h1>

</div>

<p>P2</p>
<h1>{{color}}</h1>

<script>
var app = angular.module('myApp', []);
app.run(function($rootScope) 
 {
    $rootScope.color = 'blue';
});
app.controller('myCtrl', function($scope)
 {
    $scope.color = "red";
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="personCtrl">

<p>The name is {{ lastName | uppercase }}</p>

</div>

<script>
angular.module('myApp', []).controller('personCtrl', function($scope)
 {
    $scope.firstName = "mksms",
    $scope.lastName = "kkcka"
});
</script>

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="costCtrl">

<h1>Price: {{ price | currency }}</h1>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('costCtrl', function($scope) 
 {
    $scope.price = 58;
});
</script>
</body>
</html>


<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="namesCtrl">

<ul>
  <li ng-repeat="x in names | filter : 'i'">
    {{ x }}
  </li>
</ul>

</div>

<script>
angular.module('myApp', []).controller('namesCtrl', function($scope) {
    $scope.names = [
        'a'
 'e'
 'i'
 'o'
 'u'
  ];
});
</script>

<p>This example displays only the names containing the letter "i".</p>

</body>
</html>
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="namesCtrl">

<p>Type a letter in the input field:</p>

<p><input type="text" ng-model="test"></p>

<ul>
  <li ng-repeat="x in names | filter:test">
    {{ x }}
  </li>
</ul>

</div>

<script>
angular.module('myApp', []).controller('namesCtrl', function($scope) 
 {
    $scope.names = [
        'a'
 'e'
 'i'
 'o'
 'u'
    ];
});
</script>

<p>The list will only consists of names matching the filter.</p>


</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<ul ng-app="myApp" ng-controller="namesCtrl">
<li ng-repeat="x in names">
    {{x | myFormat}}
</li>
</ul>

<script>
var app = angular.module('myApp', []);
app.filter('myFormat', function() 
 {
    return function(x) {
        var i, c, txt = "";
        for (i = 0; i < x.length; i++)
 {
            c = x[i];
            if (i % 2 == 0) {
                c = c.toUpperCase();
            }
            txt += c;
        }
        return txt;
    };
});
app.controller('namesCtrl', function($scope)
 {
    $scope.names = [
        'raj'
 'prabakar'
 'kishore'
        ];
});
</script>
</body>
</html>


 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">
<p>P</p>
<h3>{{myUrl}}</h3>
</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $location) {
    $scope.myUrl = $location.absUrl();
});
</script>

</body>
</html>
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl"> 

<p>Today's welcome message is:</p>

<h1>{{myWelcome}}</h1>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http)
 {
  $http.get("welcome.htm").then(function (response)
 {
      $scope.myWelcome = response.data;
  });
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl"> 

<p>P</p>

<h1>{{myHeader}}</h1>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $timeout) 
 {
  $scope.myHeader = "Hello World!";
  $timeout(function ()
 {
      $scope.myHeader = "the text is changed";
  }, 3000);
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl"> 

<p>Today's welcome message is:</p>

<h1>{{myWelcome}}</h1>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http) 
 {
  $http.get("welcome.htm")
  .then(function(response) {
      $scope.myWelcome = response.data;
  });
});
</script>

</body>
</html>
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl"> 

<p>Today's welcome message is:</p>

<h1>{{myWelcome}}</h1>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http)
 {
  $http({
    method : "GET",
    url : "welcome.htm"
  })
 .then(function mySuccess(response)
 {
      $scope.myWelcome = response.data;
    },
 function myError(response) 
 {
      $scope.myWelcome = response.statusText;
  });
});
</script>

</body>
</html>


<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl"> 

<p>Data : {{content}}</p>
<p>Status : {{statuscode}}</p>
<p>StatusText : {{statustext}}</p>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http)
 {
  $http.get("welcome.htm")
  .then(function(response)
 {
      $scope.content = response.data;
      $scope.statuscode = response.status;
      $scope.statustext = response.statusText;            
  });
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="customersCtrl"> 

<table>
  <tr ng-repeat="x in names">
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) {
    $http.get("customers.php")
    .then(function (response) {$scope.names = response.data.records;});
});
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<style>
table, th , td  
 {
  border: 1px solid grey;
  border-collapse: collapse;
  padding: 5px;
}
table tr:nth-child(odd) 
 {
  background-color: black
}
table tr:nth-child(even) 
 {
  background-color: blue;
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="customersCtrl"> 

<table>
  <tr ng-repeat="x in names">
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) 
 {
    $http.get("customers.php")
    .then(function (response) {$scope.names = response.data.records;});
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<style>
table, th , td  {
  border: 1px solid grey;
  border-collapse: collapse;
  padding: 5px;
}
table tr:nth-child(odd) {
  background-color: #f1f1f1;
}
table tr:nth-child(even) {
  background-color: #ffffff;
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="customersCtrl"> 

<table>
  <tr ng-repeat="x in names | orderBy : 'Country'">
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) {
    $http.get("customers.php")
    .then(function (response) {$scope.names = response.data.records;});
});
</script>

</body>
</html>

 
 
 
 <!DOCTYPE html>
<html>
<style>
table, th , td  
 {
  border: 1px solid grey;
  border-collapse: collapse;
  padding: 5px;
}
table tr:nth-child(odd)
 {
  background-color: black1;
}
table tr:nth-child(even)
 {
  background-color: blue;
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="customersCtrl"> 

<table>
  <tr ng-repeat="x in names">
    <td>{{ $index + 1 }}</td>
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) 
 {
    $http.get("customers.php")
    .then(function (response) {$scope.names = response.data.records;});
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<select ng-model="selectedName" ng-options="x for x in names">
</select>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) 
 {
    $scope.names = ["A", "B", "C"];
});
</script>
</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<p>Select a car:</p>

<select ng-model="selectedCar">
<option ng-repeat="x in cars" value="{{x.model}}">{{x.model}}</option>
</select>

<h1>You selected: {{selectedCar}}</h1>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) 
 {
    $scope.cars = [
        {model : "Porsche"},
        {model : "Audi"},
        {model : "Volvo "}
    ];
});
</script>
</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<p>Select a car:</p>

<select ng-model="selectedCar">
<option ng-repeat="x in cars" ng-value="{{x}}">{{x.model}}</option>
</select>

<h1>You selected a {{selectedCar.color}} {{selectedCar.model}}</h1>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.cars = [
        {model : "AUDI", color : "white"},
        {model : "Bmw", color : "white"},
        {model : "Benz", color : "black"}
    ];
});
</script>
 </body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<p>Select a car:</p>

<select ng-model="selectedCar" ng-options="x for (x, y) in cars">
</select>

<h1>You selected: {{selectedCar}}</h1>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) 
 {
    $scope.cars = 
 {
        car01 : "Ford",
        car02 : "Fiat",
        car03 : "Volvo"
    }
});
</script>
</body>
</html>

 
 <!DOCTYPE html>
<html >

<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>
 
<div ng-app="myApp" ng-controller="customersCtrl">
 
<table>
  <tr ng-repeat="x in names">
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>
 
</div>
 
<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) {
   $http.get("customers_mysql.php")
   .then(function (response) {$scope.names = response.data.records;});
});
</script>
 
</body>
</html>

 
 <!DOCTYPE html>
<html>

<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="customersCtrl">

<table>
  <tr ng-repeat="x in names">
    <td>{{ x.Name }}</td>
    <td>{{ x.Country }}</td>
  </tr>
</table>

</div>

<script>
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $http) {
    $http.get("customers_sql.aspx")
    .then(function (response) {$scope.names = response.data.records;});
});
</script>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="" ng-init="mySwitch=true">
<p>
<button ng-disabled="mySwitch">Click Me!</button>
</p>
<p>
<input type="checkbox" ng-model="mySwitch"/>Button
</p>
<p>
{{ mySwitch }}
</p>
</div> 

</body>
</html>

 
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">

<p ng-show="true">I am visible.</p>

<p ng-show="false">I am not visible.</p>

</div> 

</body>
</html>
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">

<p ng-show="true">this  is visible.</p>

<p ng-show="false">this is not visible.</p>

</div> 

</body>
</html>
 
 

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<h1 ng-mousemove="count = count + 1">scroll over this</h1>

<h2>{{ count }}</h2>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.count = 0;
});
</script> 

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<button ng-click="count = count + 1">Click this</button>

<p>{{ count }}</p>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.count = 0;
});
</script> 

</body>
</html>
 
 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<button ng-click="myFunc()">Click Me!</button>

<div ng-show="showMe">
    <h1>Menu:</h1>
    <div>A</div>
    <div>B</div>
    <div>B</div>
</div>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.showMe = false;
    $scope.myFunc = function()
 {
        $scope.showMe = !$scope.showMe;
    }
});
</script>

<p>Click this.</p>

</body>
</html>

<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="myCtrl">

<h1 ng-mousemove="myFunc($event)">Mouse Over Me!</h1>

<p>Coordinates: {{x + ', ' + y}}</p>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope)
 {
    $scope.myFunc = function(myE) 
 {
        $scope.x = myE.clientX;
        $scope.y = myE.clientY;
    }
});
</script> 

<p>plac the Mouse over this</p>

</body>
</html>

 <!DOCTYPE html>
<html lang="en">
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="myApp" ng-controller="formCtrl">
  <form>
    First Name: <input type="text" ng-model="firstname">
  </form>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('formCtrl', function($scope) 
 {
    $scope.firstname = "A";
});
</script>

</body>
</html>

 
<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">
  <form>
    First Name: <input type="text" ng-model="firstname">
  </form>
  <h1>You entered: {{firstname}}</h1>
</div>

<p>p.</p>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<div ng-app="">
  <form>
    Check to display a header:
    <input type="checkbox" ng-model="myVar">
  </form>
  <h1 ng-show="myVar">H</h1>
</div>

<p>P</p>

</body>
</html>

 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body ng-app="">

<form>
  Pick a topic:
  <input type="radio" ng-model="myVar" value="dogs">Dogs
  <input type="radio" ng-model="myVar" value="tuts">Tutorials
  <input type="radio" ng-model="myVar" value="cars">Cars
</form>

<div ng-switch="myVar">
  <div ng-switch-when="dogs">
     <h1>Dogs</h1>
     <p>p</p>
  </div>
  <div ng-switch-when="tuts">
     <h1>Tutorials</h1>
     <p>P</p>
  </div>
  <div ng-switch-when="cars">
     <h1>Cars</h1>
     <p>P</p>
  </div>
</div>

<p>P.</p>

</body>
</html>

 
 <!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body ng-app="">

<form>
  Select a topic:
  <select ng-model="myVar">
    <option value="">
    <option value="dogs">Dogs
    <option value="tuts">Tutorials
    <option value="cars">Cars
  </select>
</form>

<div ng-switch="myVar">
  <div ng-switch-when="dogs">
     <h1>Dogs</h1>
     <p>Welcome to a world of dogs.</p>
  </div>
  <div ng-switch-when="tuts">
     <h1>H</h1>
     <p>p.</p>
  </div>
  <div ng-switch-when="cars">
     <h1>Cars</h1>
     <p>P</p>
  </div>
</div>

<p>P</p>

</body>
</html>

 
