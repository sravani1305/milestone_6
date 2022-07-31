<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Error Handling</h2>

<p>How to use <b>catch</b> to display an error.</p>

<p id="demo"></p>

<script>
try {
  function ReverseString(talentio) {
   return talentio.split('').reverse().join('')
}
 
// Function call
talentio="anu radha"
document.write(ReverseString(talentio))
}
catch(err) {
  document.getElementById("demo").innerHTML =err.msg;
}
</script>

</body>
</html>