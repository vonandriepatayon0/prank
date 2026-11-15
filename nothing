<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Fate 💀</title>

<style>
body {
    background: #080808;
    color: white;
    font-family: Arial, sans-serif;
    text-align: center;
    height: 100vh;
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

h1 {
    color: red;
    font-size: 30px;
}

p {
    color: gray;
}

button {
    padding: 15px 25px;
    border: none;
    border-radius: 12px;
    font-size: 18px;
    cursor: pointer;
}

#yes {
    background: darkred;
    color: white;
    transition: 0.2s;
    position: relative;
    z-index: 5;
}

#no {
    background: white;
    color: black;
    position: relative;
    z-index: 6;
}

#message {
    color: red;
    font-size: 25px;
}
</style>
</head>

<body>

<h1>💀 YOU WILL DIE TODAY 💀</h1>
<p>DO YOU ACCEPT YOUR FATE?</p>

<div>
    <button id="yes" onclick="answer()">YES 💀</button>
    <button id="no" onclick="grow()">NO, I'M NOT READY 😭</button>
</div>

<h2 id="message"></h2>

<script>
let clicks = 0;
let size = 18;

function grow() {
    clicks++;
    size += 15;

    const yes = document.getElementById("yes");
    const no = document.getElementById("no");

    yes.style.fontSize = size + "px";
    yes.style.padding = (15 + clicks * 7) + "px " +
                        (25 + clicks * 12) + "px";

    if (clicks >= 3) {
        no.style.position = "fixed";
        no.style.left = Math.random() * 70 + 10 + "%";
        no.style.top = Math.random() * 70 + 10 + "%";
    }

    if (clicks >= 8) {
        yes.style.position = "fixed";
        yes.style.inset = "0";
        yes.style.width = "100vw";
        yes.style.height = "100vh";
        yes.style.borderRadius = "0";
        yes.style.fontSize = "50px";
        yes.innerHTML = "💀 YES 💀";

        // Hide NO completely
        no.style.display = "none";
    }
}

function answer() {
    document.body.innerHTML = `
        <h1 style="color:red;font-size:45px;">
        💀 GAME OVER 💀
        </h1>
        <h2>JUST KIDDING!!! 😂</h2>
        <p>YOU GOT PRANKED! ❤️</p>
    `;
}
</script>

</body>
</html>
