# github-user
<!DOCTYPE html>
<html>
<head><title>BMI</title></head>
<body>
  <input id="w" placeholder="Weight (kg)">
  <input id="h" placeholder="Height (m)">
  <button onclick="calc()">Calculate</button>
  <p id="res"></p>

  <script>
    function calc() {
     let  w = parseFloat(document.getElementById("w").value);
      let h = parseFloat(document.getElementById("h").value);
      let bmi = w / (h*h);
      document.getElementById("res").innerText = "your BMI: " + bmi.toFixed(2);
    }
  </script>
</body>
</html> ***
