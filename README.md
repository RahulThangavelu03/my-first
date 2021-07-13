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


