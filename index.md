<!DOCTYPE html>
<html>
<title>dropdown</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet" type="text/css">
<style>
    body {
        margin: 0.5rem;
        background-color: azure;
    }
    p {
        font-weight: bolder;
        color: blue;
    }
    header {
        color: blue;
        text-align: inherit;
        line-height: 3rem;
        font-weight: bolder;
    }
</style>
  <body>
      
  <header>List of Possible Combinations</header>

  

<select id="mySelect" onchange="myFunction()">

<option value=" "></option>
  <option value="Car">Car</option>
  <option value="Amusement">Amusement</option>
  <option value="Train">Train</option>
  <option value="Air">Air</option>
  <option value="Sea">Sea</option>
  <option value="Water">Water</option>
  <option value="Sub">Sub</option>
  <option value="Trade">Trade</option>
  <option value="Market">Market</option>
  <option value="Police">Police</option>
  <option value="Football">Football</option>
  <option value="Basketball">Basketball</option>
  



</select><select id="mySelect1" onchange="myFunction1()">
  <option value=" "></option>
  <option value="Park">Park</option>
  <option value="Square">Square</option>
  <option value="Place">Place</option>
  <option value="Shore">Shore</option>
  <option value="Station">Station</option>
  <option value="Field">Field</option>
  <option value="Way">Way</option>
  <option value="Fall">Fall</option>
  <option value="Port">Port</option>
  <option value="Court">Court</option>
   <option value="Fare">Fare</option>
   

</select>

<p id="demo"> Click The Words to give meaning </p>


<script>
function myFunction() {
  var x = document.getElementById("mySelect").value;
  var y = document.getElementById("mySelect1").value;
  document.getElementById("demo").innerHTML =  "Word is " + x  +y;

}
function myFunction1() {
  var x = document.getElementById("mySelect").value;
  var y = document.getElementById("mySelect1").value;
  document.getElementById("demo").innerHTML =  "Word is " + x  +y;

}
</script>
</body>
</html>
