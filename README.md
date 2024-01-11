
<!DOCTYPE html>
<html>
<body>
<form action="NEWPHP.php" method="POST">
<h1 title="Registration Form">Registration form</h1>
<label title="Pangalan" for="fname"><b>First name:</b></label><br>
<input type="text" id="fname" name="fname"><br>
<label title="Gitnang pangalan"for="mname"><b>Middle name:</b></label><br>
<input type="text" id="mname" name="mname"><br>
<label title="Apelyido"for="lname"><b>Last name:</b></label><br>
<input type="text" id="lname" name="lname"><br>
<label title="Email" for="email"><b>Email:</b></label><br>
<input type="text" id="email"><br>
<label title="Kasarian" for="Sex"><b>Sex:</b></label><br>
<select sex="sex" id="sex"><br>
  <option title="Lalaki" value="Male"><b>Male</b></option><br>
  <option title="Babae" value="Female"><b>Female</b></option><br>
</select>
<br>
<label title="Mga subjects na napag-aralan"for="Subjects Taken"><b>Subjects Taken:</b></label><br>
<input type="checkbox" id="sj1" name="Math" value="Math">
<label for="Math"><b>Math</b></label>
<input type="checkbox" id="sj2" name="Science" value="Science">
<label for="Science"><b>Science</b></label><br>
<input type="checkbox" id="sj3" name="Filipino" value="Filipino">
<label for="Filipino"><b>Filipino</b></label>
<input type="checkbox" id="sj4" name="English" value="English">
<label for="English"><b>English</b></label><br><br>
<input type="reset" value="Reset"><br>
<input type="submit" value="Submit">
</form>
</body>
</html>
