<!DOCTYPE html>
<html>
<head>
<style> 
body {
	background-color: #CCCCCC;
}
h1{
	background-color: #;
}
P{
	background-color: #FF0000;
}
</style>
<bgcolor>
<title>Page Title</title>
</bgcolor></head>
<body style="background-color: #CCCCCC;">

<center>


<style> {
font-family: arial, sans-serif;
border-collapse: collapse;
width:100%;
}
td, th{
border: 1px solid #dddddd;
text-align left;
padding 8px;
}
	tr:nth-child(even){
	background-color.#dddddd;
}
</style>

</center></body>
<table align="center">
<tr>
<th style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Name</th>
<th style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Nickname</th>
<th style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Interest</th>
<th style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Hobbies</th>
</tr>

<tr>
<td style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Job G. Brioso</td>
<td style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">"Job"</td>
<td style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Basketball and Fitness</td>
<td style="border: 1px solid #dddddd;text-align left: ;padding 8px: ;">Surfing in the internet, playing basketball, working out.</td>
</tr>
<center>
<h2>Basketball</h2>
<img src="bb.jpeg" alt="Basketball" style="width:700px;height:400px;">
<h3>Fitness</h3>
<img src="fitness.jpg" alt="Fitness" style="width:700px;height:400px;">

<h1>Trivias about me!</h1>

<h1 id="Q1">My sports?</h1>
<button type="button" onclick="document.getElementById('Q1').innerHTML = 'Basketball'">Click to know</button>
<h1 id="Q2">My Traits?</h1>
<button type="button" onclick="document.getElementById('Q2').innerHTML = 'OPTIMIST'">Click to know</button>
<h1 id="Q3">My favorite food?</h1>
<button type="button" onclick="document.getElementById('Q3').innerHTML = 'Sea foods'">Click to know</button>
<h1 id="Q4">What I want to become in future??</h1>
<button type="button" onclick="document.getElementById('Q4').innerHTML = 'Navy Seal'">Click To Know!</button>
<h1 id="Q5">My motto in life?</h1>
<button type="button" onclick="document.getElementById('Q5').innerHTML = 'Faith changes evrything!'">Click To Know!</button>

<br><br>


<?php
// define variables and set to empty values
$nameErr = $emailErr = $genderErr = $websiteErr = "";
$name = $email = $gender = $comment = $website = "";

if ($_SERVER["REQUEST_METHOD"] == "POST") {
  if (empty($_POST["name"])) {
    $nameErr = "Name is required";
  } else {
    $name = test_input($_POST["name"]);
    // check if name only contains letters and whitespace
    if (!preg_match("/^[a-zA-Z ]*$/",$name)) {
      $nameErr = "Only letters and white space allowed"; 
    }
  }
  
  if (empty($_POST["email"])) {
    $emailErr = "Email is required";
  } else {
    $email = test_input($_POST["email"]);
    // check if e-mail address is well-formed
    if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
      $emailErr = "Invalid email format"; 
    }
  }
    
  if (empty($_POST["website"])) {
    $website = "";
  } else {
    $website = test_input($_POST["website"]);
    // check if URL address syntax is valid (this regular expression also allows dashes in the URL)
    if (!preg_match("/\b(?:(?:https?|ftp):\/\/|www\.)[-a-z0-9+&@#\/%?=~_|!:,.;]*[-a-z0-9+&@#\/%=~_|]/i",$website)) {
      $websiteErr = "Invalid URL"; 
    }
  }

  if (empty($_POST["comment"])) {
    $comment = "";
  } else {
    $comment = test_input($_POST["comment"]);
  }

  if (empty($_POST["gender"])) {
    $genderErr = "Gender is required";
  } else {
    $gender = test_input($_POST["gender"]);
  }
}

function test_input($data) {
  $data = trim($data);
  $data = stripslashes($data);
  $data = htmlspecialchars($data);
  return $data;
}
?>
<h2>Fill up your online life now!</h2>
<p><span class="error">* required field.</span></p>
<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">  
  Name: <input type="text" name="name" value="<?php echo $name;?>">
  <span class="error">* <?php echo $nameErr;?></span>
  <br><br>
  E-mail: <input type="text" name="email" value="<?php echo $email;?>">
  <span class="error">* <?php echo $emailErr;?></span>
  <br><br>
  Website: <input type="text" name="website" value="<?php echo $website;?>">
  <span class="error"><?php echo $websiteErr;?></span>
  <br><br>
  Comment: <textarea name="comment" rows="5" cols="40"><?php echo $comment;?></textarea>
  <br><br>
  Gender:
  <input type="radio" name="gender" <?php if (isset($gender) && $gender=="female") echo "checked";?> value="female">Female
  <input type="radio" name="gender" <?php if (isset($gender) && $gender=="male") echo "checked";?> value="male">Male
  <span class="error">* <?php echo $genderErr;?></span>
  <br><br>
  <input type="submit" name="submit" value="Submit">  
</form>
</center>
</table>
</html>