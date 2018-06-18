Checkpoint: Create an html form that includes the following fields: email input, password input, Github username input, account type radio, remember me checkbox.

![Preview](/Users/arthurapplegate/Documents/GitHub/bucket1/forms2-html/preview.png)

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Create Account</title>
    <link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
    <link rel="stylesheet" href="./main.css">
  </head>
  <body>
    <header class="words">
      <h1>Create Account</h1>
    </header>
    <form class="words" action="index.html" method="post">
      <!-- Email -->
      <div class="email"><input type="email" name="em" value="" placeholder="Email" required>
      </div>
      <br>
      <!-- Password -->
      <div class="password"><input type="password" name="pw" pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{6,}" title="Must include one lowercase,uppercase,and number" placeholder="Password" required>
      </div>
      <br>
      <!-- Github Username -->
      <div class="github"><input type="text" name="git" value="" placeholder="Github Username">
      </div>
      <br>
      <!-- Radio buttons with the following options: Enterprise, Pro, Free -->
      <div class="githubtype"> Account Type: <br>
        <br>
        <input type="radio" name="gtype" value=""> Enterprise <br>
        <input type="radio" name="gtype" value=""> Pro <br>
        <input type="radio" name="gtype" value=""> Free <br>
      </div>
      <br>
      <!-- A checkbox with the words "Remember Me" next to it. -->
      <div class="remember">
        <input type="checkbox" name="rm" checked> Remember Me <br>
      </div>
      <br>
      <button type="submit" name="submit">Submit</button>
    </form>
  </body>
</html>
```
