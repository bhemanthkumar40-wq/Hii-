

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