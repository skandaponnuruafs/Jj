
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Gamuy Game</title>
<style>
body {
  background: #101827;
  color: white;
  font-family: Arial;
  text-align: center;
  padding-top: 40px;
}
button {
  font-size: 28px;
  padding: 18px;
  border: none;
  border-radius: 15px;
  background: #38bdf8;
}
</style>
</head>
<body>
<h1>🎮 GAMUY</h1>
<h2>Tap the Target!</h2>
<p>Score: <span id="score">0</span></p>
<button onclick="hit()">🎯 TAP ME</button>
<p id="msg">Let's play!</p>
<script>
let score = 0;
function hit() {
  score++;
  document.getElementById("score").textContent = score;
  document.getElementById("msg").textContent =
    "Awesome! Keep going!";
}
</script>
</body>
</html>
