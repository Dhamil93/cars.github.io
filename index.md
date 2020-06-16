<!DOCTYPE html>
<html>
  <style>
    p {
      color: blue;
      font-style: italic;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bolder;
    }
  </style>
<body>

<p>Select a new car from the list.</p>

<select id="mySelect" onchange="myFunction()">
  <option value="Audi"></option>
  <option value="Acura">Acura</option>
  <option value="Audi">Audi</option>
  <option value="BMW">BMW</option>
  <option value="Ford">Ford</option>
  <option value="Mercedes">Mercedes</option>
  <option value="Toyota">Toyota</option>
  <option value="Volvo">Volvo</option>
  
  
</select>

<p>When you select a new car, a function is triggered which outputs the value of the selected car.</p>

<p id="demo"></p>

<script>
function myFunction() {
  var x = document.getElementById("mySelect").value;
  document.getElementById("demo").innerHTML = "You selected: " + x;
}
</script>

</body>
</html>
