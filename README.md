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
<p>P</p>

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

 
 

