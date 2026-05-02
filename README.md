<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Riyansh Gaming</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: black;
    color: white;
    text-align: center;
}

/* Neon Animated Title */
h1 {
    font-size: 50px;
    margin-top: 100px;
    animation: glow 1.5s infinite alternate;
}

@keyframes glow {
    0% { text-shadow: 0 0 10px red, 0 0 20px red; }
    100% { text-shadow: 0 0 20px cyan, 0 0 40px cyan; }
}

/* Button Animation */
.btn {
    margin-top: 20px;
    padding: 12px 25px;
    background: cyan;
    color: black;
    border: none;
    font-size: 18px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background: red;
    color: white;
    transform: scale(1.1);
}

/* Background Animation */
body::before {
    content: "";
    position: fixed;
    width: 200%;
    height: 200%;
    background: linear-gradient(45deg, red, blue, purple, cyan);
    animation: move 10s linear infinite;
    z-index: -1;
    opacity: 0.2;
}

@keyframes move {
    0% { transform: translate(0,0); }
    100% { transform: translate(-50%, -50%); }
}
</style>

</head>

<body>

<h1>🔥 RIYANSH OP GAMING 🔥</h1>
<p>Welcome to My Gaming World 🎮</p>

<button class="btn">Subscribe</button>

</body>
</html>
