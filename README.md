<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Империя Zz - Онлайн дүкен</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Империя Zz</h1>
        <p>Сапалы тауарлар мен қызметтердің мекені</p>
    </header>

    <nav>
        <ul>
            <li><a href="#">Басты бет</a></li>
            <li><a href="#">Қызметтер</a></li>
            <li><a href="#">Байланыс</a></li>
        </ul>
    </nav>

    <section id="products">
        <h2>Біздің өнімдер</h2>
        <div class="product">
            <img src="product1.jpg" alt="Өнім 1">
            <h3>Өнім атауы</h3>
            <p>Қысқаша сипаттама</p>
            <button onclick="orderNow()">Сатып алу</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Өнім 2">
            <h3>Өнім атауы</h3>
            <p>Қысқаша сипаттама</p>
            <button onclick="orderNow()">Сатып алу</button>
        </div>
    </section>

    <footer>
        <p>Барлық құқықтар қорғалған &copy; 2025 - Империя Zz</p>
    </footer>

    <script src="script.js"></script>
</body>
</html> body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f8f8f8;
}

header {
    background-color: #222;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #222;
    font-weight: bold;
}

section {
    padding: 20px;
}

.product {
    display: inline-block;
    width: 200px;
    margin: 20px;
    padding: 10px;
    background: white;
    box-shadow: 0px 0px 10px #ccc;
    border-radius: 10px;
}

.product img {
    width: 100%;
    border-radius: 5px;
}

button {
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    cursor: pointer;
    margin-top: 10px;
}

button:hover {
    background-color: #218838;
}

footer {
    background-color: #222;
    color: white;
    padding: 10px;
    margin-top: 20px;
} function orderNow() {
    alert("Тапсырыс беру үшін WhatsApp-қа хабарласыңыз: +7 777 777 77 77");
}
