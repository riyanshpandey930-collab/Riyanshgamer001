<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Riyansh Gaming</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: black;
    color: white;
    text-align: center;
}

/* Intro Screen */
#intro {
    position: fixed;
    width: 100%;
    height: 100%;
    background: black;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    z-index: 9999;
}

/* Loading Text */
.loading {
    font-size: 30px;
    animation: blink 1s infinite;
}

@keyframes blink {
    50% { opacity: 0.3; }
}

/* Progress Bar */
.bar {
    width: 200px;
    height: 10px;
    background: #333;
    margin-top: 20px;
}

.fill {
    width: 0%;
    height: 100%;
    background: cyan;
    animation: load 3s linear forwards;
}

@keyframes load {
    0% { width: 0%; }
    100% { width: 100%; }
}

/* Main Content */
#main {
    display: none;
}

/* Neon Title */
h1 {
    font-size: 50px;
    margin-top: 100px;
    animation: glow 1.5s infinite alternate;
}

@keyframes glow {
    0% { text-shadow: 0 0 10px red; }
    100% { text-shadow: 0 0 20px cyan; }
}
</style>
</head>

<body>

<!-- Intro Screen -->
<div id="intro">
    <div class="loading">Loading Riyansh Gaming...</div>
    <div class="bar">
        <div class="fill"></div>
    </div>
</div>

<!-- Main Website -->
<div id="main">
    <h1>🔥 RIYANSH OP GAMING 🔥</h1>
    <p>Welcome to My Gaming World 🎮</p>
</div>

<script>
// After 3 seconds hide intro
setTimeout(() => {
    document.getElementById("intro").style.display = "none";
    document.getElementById("main").style.display = "block";
}, 3000);
</script>

</body>
</html>
