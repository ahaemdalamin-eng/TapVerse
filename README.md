# TapVerse
 My free app project
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>TapVerse</title>
</head>
<body>
<h1>TapVerse</h1>
<h2>🪙 Coins: <span id="coins">0</span></h2>
<button onclick="tap()">TAP ME</button>
<script>
let coins = 0;
function tap() {
coins++;
document.getElementById("coins").innerText = coins;
}
</script>
</body>
</html>
