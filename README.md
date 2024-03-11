<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obchod s nalepkami</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Vitaj v HuligensShop</h1>
        <nav>
            <ul>
                <li><a href="#">Domov</a></li>
                <li><a href="#">O nás</a></li>
                <li><a href="#">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Naše najpredávanejšie nalepky</h2>
            <div class="sticker">
                <img src="sticker1.jpg" alt="Nalepka 1">
                <p>Nalepka 1 - 5€</p>
            </div>
            <div class="sticker">
                <img src="sticker2.jpg" alt="Nalepka 2">
                <p>Nalepka 2 - 7€</p>
            </div>
            <!-- Ďalšie nalepky -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Obchod s nalepkami</p>
    </footer>
</body>
</html>
/* Základné štýly pre celú stránku */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Štýly pre header */
header {
    background-color: #333;
    color: #4EFF01;
    padding: 20px;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Štýly pre main */
main {
    padding: 20px;
}

.sticker {
    margin-bottom: 20px;
}

.sticker img {
    width: 200px;
    height: 200px;
    margin-right: 10px;
}

/* Štýly pre footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
