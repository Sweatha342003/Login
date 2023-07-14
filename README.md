<!DOCTYPE html>
<html>
<head>
  <title>Login Page</title>
</head>
<style>
    .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-size: 30px;
  }

  body {
    background-image: url('https://cdn.wallpapersafari.com/95/40/LkN3Ej.png');
    background-repeat: no-repeat;
    background-image: cover;
  }
  
  
  form {
    width: 400px;
    padding: 50px;
    background: #1e6cb4;
    border-radius: 5px;
  }
  
  h2 {
    text-align: center;
  }
  
  .form-group {
    margin-bottom: 10px;
  }
  
  label {
    display: block;
    margin: bottom 5px;;
  }
  
  input[type="text"],
  input[type="password"] {
    width: 100%;
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 1px;
  }
  
  button {
    width: 100%;
    padding: 10px;
    background: #4CAF50;
    border: none;
    color: #fff;
    cursor: pointer;
    border-radius: 3px;
  }
  
button:hover {
    background: #45a049;
  }
</style>
<body>
  <div class="container">
    <form>
      <h2>AI Sign up</h2>
      <div class="form-group">
        <label for="username">Firstname</label>
        <input type="text" id="Firstname" name="Firstname" required>
      </div>
      <div class="form-group">
        <label for="Lastname">Lastname</label>
        <input type="password" id="Lastname" name="Lastname" required>
      </div>
      <div class="form-group">
        <label for="Mail Id">Mail Id</label>
        <input type="password" id="Mail Id" name="Mail Id" required>
      </div>
      <div class="form-group">
        <label for="Phone Number">Phone Number</label>
        <input type="password" id="Phone Number" name="Phone Number" required>
      </div>
      <div class="form-group">
        <label for="Gender">Gender</label>
        <select name="gender"id="gender">
            <option>select</option>
            <option value="Male">Male</option>
            <option value="emale">Female</option>
            <option value="Others">Others</option>
        </select>
      </div>
      <div class="form-group">
        <label for="Notification">Notification</label>
        <select name="Notification"id="Notification">
            <option>select</option>
            <option value="For SMS Notification">For SMS Notification</option>
            <option value="For Mail Notification">For Mail Motification</option>
            <option value="For Message Notification">For Message Motification</option>
        </select>
      </div>
      <button type="submit">Create Account</button>
    </form>
  </div>
</body>
</html>
