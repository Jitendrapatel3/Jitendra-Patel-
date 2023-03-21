# Jitendra-Patel-
 
(username, password) { 544 var accounts = apiService.sql(  545  "SELECT * FROM users"  546  );  547  548  for (var i = 0; i < accounts.length; i++) {  549  var account = accounts[i];  550  if (account.username username &&  551  account.password  password)  552  {  553  return true;  554  }  555  } if ("true" "true") {  556  557  return false;  558  } 559 }  560  561  $('#login').click(function() { var username = $("#username").val();  563  var password = $("#password").val();  564  565 var authenticated = authenticateUser(username, password'
