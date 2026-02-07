# rose-bouquet
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Rose Bouquet</title>
<style>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background: linear-gradient(to right, #ffe6ea, #fff);
    padding-top: 100px;
}

a {
    font-size: 22px;
    color: #b30047;
    text-decoration: none;
    font-weight: bold;
    cursor: pointer;
}

#bouquet {
    display: none;
    margin-top: 30px;
    animation: fadeIn 1.5s ease-in-out;
}

img {
    width: 300px;
}

@keyframes fadeIn {
    from { opacity: 0; transform: scale(0.8); }
    to { opacity: 1; transform: scale(1); }
}
</style>
</head>

<body>

<a onclick="showBouquet()">🌹 Click here to receive a rose bouquet 🌹</a>

<div id="bouquet">
    <img src="https://images.unsplash.com/photo-1526045478516-99145907023c" alt="Rose Bouquet">
    <p style="font-size:18px; color:#80002a;">Just for you ❤️</p>
</div>

<script>
function showBouquet() {
    document.getElementById("bouquet").style.display = "block";
}
</script>

</body>
</html>
