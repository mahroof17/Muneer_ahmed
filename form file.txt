
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Page Title</title>
    
</head>
<style type="text/css">
    fieldset{
        text-align: center;
        width: 250px;
        height: 250px;
        color: gray;
        background: skyblue;
        border-radius: 10px;
    }
</style>
<body style="background: skyblue">
    <center>
   <fieldset>
    <form action="#" method="POST">
       <legend>Form Submit</legend>
       <tr> 
        <td>Name</td>
        <td><input type="text" name="name"></td>
        <br><br>
         <td>Address</td>
         <td><input type="text" name="address"></td>
         <br><br>
          <input type="submit" name="submit" value="submit">
           </tr>
           </form>
   </fieldset>
   </center>

  <?php

  <!-- print($_REQUEST); -->
  var_dump($_REQUEST);
 <!--  if(isset($_POST['submit'])){
  $name=$_POST['name'];
  $address=$_POST['address']
} -->
  

  ?> 
</body>
</html>

