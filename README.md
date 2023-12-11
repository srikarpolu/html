# html
I have started to learn front-end developing
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sample Form</title>
</head>
<body>

  <h2>Contact Information</h2>

  <form action="/submit" method="post">
    <label for="firstName">First Name:</label>
    <input type="text" placeholder="firstName" id="firstName" name="firstName" required><br>
    <input type="date" name="birthdate">
    <hr>
    <br>4
    <label for="cars">Choose a car:</label>
<select id="cars" name="cars" required>
    <option value="Null">Null</option>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
    <br>
    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName" name="lastName" required>
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    <br>
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="6" required></textarea>


    <input type="submit" value="Submit">
  </form>

</body>
</html>
