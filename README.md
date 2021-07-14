# my-first
<!DOCTYPE HTML>
<html>
  <body>
    <?PHP>
echo "My first php code ";
?>
  </body>
  </html>
  
  
  Variable declaration:(global)
  
  <!DOCtype HTML>
  <Html>
  <?php>
$x = 10; 
 
function myfunction() {
  echo "<p>Variable x inside function is: $x</p>";
} 
myfunvtion();

echo "<p>Variable x outside function is: $x</p>";
?>

</body>
</html>

  local variable declaration:
  
 <!DOCTYPE html>
<html>
<body>

<?php
function myfunction() {
  $x = 56; 
  echo "<p>Variable x inside function is: $x</p>";
} 
myfunction();
echo "<p>Variable x outside function is: $x</p>";
?>
</body>
</html>

keywords:

<!DOCTYPE html>
<html>
<body>

<?php
$x = 5;
$y = 10;

function myTest() {
  global $x, $y;
  $y = $x + $y;
} 

my function();  
echo $y; 
?>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<?php
$t = date("H");

if ($t < "20")
 {
  echo "Have a nice day!";
}
 else
 {
  echo " good night!";
}
?>
 </body>
  </html>
  
  <!DOCTYPE html>
<html>
<body>

<?php
$favcolor = "red";

switch ($favcolor) {
  case "red":
   echo "Your fav color is red!";
    break;
  case "blue":
    echo "Your fav color is blue!";
    break;
  case "green":
    echo "Your fav color is green!";
    break;
  default:
    echo "Your fav color is not red, blue, nor green!";
}
?>
 
</body>
</html>

<!DOCTYPE html>
<html>
<body>

<?php  
$x = 1;
 
while($x <= 5) {
  echo "The number is $x <br>";
  $x++;
} 
?>  

</body>
</html>

<!DOCTYPE HTML>

<html>
  <body>
    <?php>
<!DOCTYPE html>
<html>
<body>

<?php 
$x = 75;
$y = 25; 

function addition()
 {
  $GLOBALS['z'] = $GLOBALS['x'] + $GLOBALS['y'];
}

addition();
echo $z;
?>

</body>
</html>
<!DOCTYPE html>
<html>
<body>

<?php 
$x = 7;
$y = 77; 

function add() 
{
  $GLOBALS['z'] = $GLOBALS['x'] + $GLOBALS['y'];
}

add();
echo $z;
?>
</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h1>The onclick Event</h1>

<p>Click  button  id="demo".</p>

<button onclick="myFunction()">Click </button>

<p id="demo"></p>

<script>
function myFunction()
  {
  document.getElementById("demo").innerHTML = "Hello World";
}
</script>

</body>
</html>

<!DOCTYPE HTML>
<html>  
<body>

<form action="welcome_get.php" method="get">
Name: <input type="text" name="name"><br>
E-mail: <input type="text" name="email"><br>
<input type="submit">
</form>

</body>
</html>


<!DOCTYPE html>
<html>
<body>

<form method="post" action="<?php echo $_SERVER['PHP_Self;?>">
  Name: <input type="text" name="fname">
  <input type="submit">
</form>

<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") 
{
    $name = chars($_REQUEST['fname']);
    if (empty($name))
 {
        echo Name is empty;
    }
 else {
        echo $name;
    }
}
?>

</body>
</html>


