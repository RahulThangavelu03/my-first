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


