<!DOCTYPE html>
<html>
<head>
  <title>Form Example</title>
</head>
<body>
  <h1>Registration Form</h1>
  <form>
    <label for="fname">First Name:</label><br>
    <input type="text" id="fname" name="fname" required><br><br>

    <label for="lname">Last Name:</label><br>
    <input type="text" id="lname" name="lname" required><br><br>

    <label for="mobile">Mobile Number:</label><br>
    <input type="tel" id="mobile" name="mobile" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="address">Address:</label><br>
    <textarea id="address" name="address" rows="4" cols="30" required></textarea><br><br>

    <input type="submit" value="Submit">
  </form>
</body>
</html>
