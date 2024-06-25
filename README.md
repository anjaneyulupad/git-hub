# git-hub
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Sign Up</title>
  <style>
    .submit-button {
        background-color: blue;
        color: white;
        padding: 10px 20px;
        border: none;
        cursor: pointer;
        border-radius: 10px;
        font-size: 16px;
         width: 15%;
          height: 20%;
    }
    .submit-button:hover {
        background-color: blue;
    }
    .container {
        text-align: center;
        margin: 0 auto;
      }
      .title-container {
    text-align: center;
}
.title-container h2 {
}
  </style>
</head>
<body>
<div class="title-container">
      <h2>Sign Up</h2>
</div>
  <form action="/submit-form-handler" method="POST">
      <div class="container">
    <div class="username">
      <label for="email">Username:</label><br>
      <input type="text" id="username" name="username" class="centered" required><br><br>
      </div>
    STATES:<br>
     <div class="STATES">
    <select id="ddlstates">
      <option>Netherlands</option>
    </select><br><br>


    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>

    <label for="confirm_password">Confirm Password:</label><br>
    <input type="password" id="confirm_password" name="confirm_password" required><br><br>
     </div>
    <div class="submit">
      <button type="submit" class="submit-button">submit</button></div>
  </form>
</body>
</html>
