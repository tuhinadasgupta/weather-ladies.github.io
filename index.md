<html>
<body>

<h2>IOT PROJECT</h2>

<form action="" method="POST">
  <label for="city">City: </label><br>
  <input type="text" id="city" name="city" value="{{request.form.city}}" required><br>
  <label for="state">State: </label><br>
  <input type="text" id="state" name="state" value="{{request.form.state}}" required><br>
  <label for="country">Country Code: </label><br>
  <input type="text" id="country" name="country" value="{{request.form.country}}" required><br>
  <br>
  <input type="submit" value="Submit">
</form> 

</body>
</html>
