<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Shruti 🎉</title>

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ffd6f6, #d6e6ff);
  text-align: center;
  overflow-x: hidden;
}

h1 {
  margin-top: 30px;
  font-size: 2.5rem;
  color: #ff4da6;
}

.hero img {
  width: 250px;
  border-radius: 20px;
  box-shadow: 0 0 20px rgba(255, 77, 166, 0.5);
  margin-top: 20px;
}

.section {
  padding: 30px 20px;
}

.message-box {
  background: white;
  margin: 20px auto;
  padding: 20px;
  border-radius: 15px;
  width: 85%;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

button {
  padding: 12px 25px;
  font-size: 16px;
  border: none;
  border-radius: 25px;
  background: #ff4da6;
  color: white;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #ff1a8c;
}

.gallery img {
  width: 150px;
  margin: 10px;
  border-radius: 15px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

.countdown {
  font-size: 20px;
  font-weight: bold;
  color: #333;
}

footer {
  margin: 30px;
  font-size: 14px;
  color: #555;
}
</style>
</head>

<body>

<h1>Happy Birthday Shruti 🎉💖</h1>

<div class="hero">
  <img src="shruti1.jpg" alt="Shruti Photo">
</div>

<div class="section">
  <div class="message-box">
    <h2>💖 Thank You For Everything</h2>
    <p>Thank you for always being there. Life is more fun and crazy because of you!</p>
  </div>

  <div class="message-box">
    <h2>😂 Crazy Memories Partner</h2>
    <p>From random selfies to nonstop laughter — best memories are always with you.</p>
  </div>

  <div class="message-box">
    <h2>🌸 Forever Bestie Promise</h2>
    <p>No matter what happens, best friend tag will always be yours!</p>
  </div>
</div>

<div class="section">
  <h2>🎂 Countdown to 6 March</h2>
  <div class="countdown" id="countdown"></div>
</div>

<div class="section">
  <h2>📸 Our Memories</h2>
  <div class="gallery">
    <img src="shruti1.jpg">
    <img src="shruti2.jpg">
  </div>
</div>

<div class="section">
  <button onclick="showSurprise()">Click for Surprise 🎁</button>
</div>

<footer>
Made with 💙 by your bestie
</footer>

<script>
// Countdown
var birthday = new Date("March 6, 2026 00:00:00").getTime();

var x = setInterval(function() {
  var now = new Date().getTime();
  var distance = birthday - now;

  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

  document.getElementById("countdown").innerHTML =
  days + "d " + hours + "h " + minutes + "m ";

}, 1000);

// Surprise
function showSurprise() {
  alert("You are my forever bestie and I’m lucky to have you! 💖");
}
</script>

</body>
</html>
