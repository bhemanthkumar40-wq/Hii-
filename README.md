<!DOCTYPE html>
<html>
<head>
<title>For Bindu ❤️</title>

<style>
body {
    background: linear-gradient(45deg, #ff9a9e, #fad0c4, #fad0c4, #ffdde1);
    text-align: center;
    font-family: Arial, sans-serif;
    overflow-x: hidden;
}

h1 {
    margin-top: 30px;
    font-size: 40px;
    color: white;
    text-shadow: 2px 2px 5px black;
}

.love-text {
    font-size: 22px;
    font-weight: bold;
    animation: glow 1s infinite alternate;
}

@keyframes glow {
    from { text-shadow: 0 0 5px white; }
    to { text-shadow: 0 0 20px yellow; }
}

button {
    padding: 12px 25px;
    font-size: 18px;
    background: red;
    color: white;
    border: none;
    border-radius: 20px;
    cursor: pointer;
    margin-top: 20px;
}
</style>

</head>
<body>

<h1>💖 Bindu I Love You ❤️ 💖</h1>

<button onclick="printLove()">Click for Surprise 😍</button>

<div id="output"></div>

<script>
function getRandomColor() {
    const colors = ["red","blue","green","purple","orange","pink","yellow"];
    return colors[Math.floor(Math.random() * colors.length)];
}

function printLove() {
    let text = "";
    for (let i = 0; i < 100; i++) {
        text += `<div class="love-text" style="color:${getRandomColor()}">
                 Bindu I Love You ❤️
                 </div>`;
    }
    document.getElementById("output").innerHTML = text;
}
</script>

</body>
</html>

 