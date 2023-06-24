<!DOCTYPE html>
<html>
<head>
  <title>Library System</title>
  <style>
    /* CSS styling for the page */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .navbar {
      background-color: #333;
      color: #fff;
      padding: 10px;
    }

    .navbar a {
      color: #fff;
      text-decoration: none;
      margin-right: 15px;
    }

    table {
      border-collapse: collapse;
      width: 100%;
    }

    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }
    .registration-form {
      max-width: 700px;
      margin: 40px auto;
      padding: 20px;
      background-color: #f2f2f2;
      border: 1px solid #ddd;
    }

    .registration-form label {
      display: block;
      margin-bottom: 10px;
    }

    .registration-form input[type="text"],
    .registration-form input[type="email"],
    .registration-form input[type="password"],
    .registration-form input[type="date"],
    .registration-form input[type="number"] {
      width: 100%;
      padding: 8px;
      margin-bottom: 10px;
    }

    .registration-form input[type="submit"] {
      background-color: #333;
      color: #fff;
      width: 100%;
      border: none;
      padding: 8px;
      cursor: pointer;
    }

    
  </style>
</head>
<body>
  <!-- Navigation Bar -->
  <div>
    <h3>Books</h3>
  </div>

  <!-- Book Table -->
  <table style="border: 2px;">
    <thead>
      <tr>
        <th>Book Id</th>
        <th>Title</th>
        <th>Author</th>
        <th>Genre</th>
        <th>Availability</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1</td>
        <td>Book Title 1</td>
        <td>Author Name 1</td>
        <td>Genre 1</td>
        <td>Available</td>
      </tr>
      <tr>
        <td>2</td>
        <td>Book Title 2</td>
        <td>Author Name 2</td>
        <td>Genre 2</td>
        <td>Not Available</td>
      </tr>
      <tr>
        <td>3</td>
        <td>Book Title 3</td>
        <td>Author Name 3</td>
        <td>Genre 3</td>
        <td>Available</td>
      </tr>
      <!-- Add more rows for additional books -->
    </tbody>
  </table>

  <!-- Registration Form -->
  <div class="registration-form">
    <h2>Register</h2>
    <form>
      <label for="firstName">First Name:</label>
      <input type="text" id="firstName" name="firstName" required>

      <label for="lastName">Last Name:</label>
      <input type="text" id="lastName" name="lastName" required>

      <label for="dob">Date Of Birth:</label>
      <input type="date" id="dob" name="dob" required>

      <label for="age">Age:</label>
      <input type="number" id="age" name="age" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

      <label for="confirmPassword">Confirm Password:</label>
      <input type="password" id="confirmPassword" name="confirmPassword" required>

      <input type="submit" value="Register">
    </form>
  </div>
</body>
</html>
