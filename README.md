<html>
<head>
  <title>Student Feedback Form</title>
</head>
<body>

<h2>Student Feedback Form</h2>

<form>

  Name:<br>
  <input type="text" id="name" name="username" placeholder="Enter your name" required><br><br>

  Email:<br>
  <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

  Department:<br>
  <select name="department" id="dept">
    <option value="cse">CSE</option>
    <option value="ece">ECE</option>
    <option value="mech">MECH</option>
  </select><br><br>

  Rating:<br>
  <input type="radio" name="rating" value="excellent"> Excellent
  <input type="radio" name="rating" value="good"> Good
  <input type="radio" name="rating" value="average"> Average<br><br>

  Comments:<br>
  <textarea name="comments" placeholder="Enter your comments"></textarea><br><br>

  <input type="submit" value="Send Feedback">

</form>

</body>
</html>
