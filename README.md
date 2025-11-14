<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Книжковий Рай</title>

    <!-- Підключення шрифтів -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Lora:wght@700&display=swap" rel="stylesheet">

    <!-- Підключення CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- ГОЛОВНА СЕКЦІЯ -->
<main class="section-main">
    <img class="section-main-logo" src="https://upload.wikimedia.org/wikipedia/commons/8/89/Book_font_awesome.svg" alt="логотип">
    <h1 class="section-main-title">Книжковий Рай</h1>
    <h2 class="section-main-subtitle">Відкрий для себе наступну чудову книгу</h2>
    <button class="section-main-button">Дізнатися більше</button>
</main>

<!-- ПРО БІБЛІОТЕКУ -->
<section class="second-section">
    <img src="https://images.pexels.com/photos/159711/books-book-pages-read-literature-159711.jpeg" alt="Бібліотека" class="second-section-img">

    <div class="second-section-info">
        <h3 class="section-subtitle">ЛАСКАВО ПРОСИМО ДО КНИЖКОВОГО РАЮ</h3>
        <h3 class="section-title">Про Нашу Бібліотеку</h3>
        <p class="second-section-text">
            "Ласкаво просимо до нашої бібліотеки, де ви знайдете широкий вибір книг для будь-якого віку та вподобань. 
            Приходьте та насолоджуйтеся читанням у затишній атмосфері."
        </p>
        <p class="second-section-name">
            <span class="second-section-name2">ІВАН ІВАНЕНКО</span> – Засновник Книжкового Раю
        </p>
    </div>
</section>

<!-- НАША КОЛЕКЦІЯ -->
<section class="third-section">
    <h3 class="section-subtitle">РЕКОМЕНДОВАНІ КНИГИ</h3>
    <h3 class="section-title">Наша Колекція</h3>

    <div class="third-section-books">

        <div class="third-section-book">
            <img src="https://upload.wikimedia.org/wikipedia/en/0/05/The_little_prince.jpg"
                 alt="Маленький принц" class="book-img">
            <h4 class="book-title">Маленький принц</h4>
            <p class="book-author">Антуан де Сент Екзюпері</p>
            <p class="book-price">150 грн</p>
        </div>

        <div class="third-section-book">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Alice_in_Wonderland_cover.jpg"
                 alt="Аліса в Країні Див" class="book-img">
            <h4 class="book-title">Аліса в Країні Див</h4>
            <p class="book-author">Льюїс Керролл</p>
            <p class="book-price">200 грн</p>
        </div>

        <div class="third-section-book">
            <img src="https://upload.wikimedia.org/wikipedia/en/c/c3/1984first.jpg"
                 alt="1984" class="book-img">
            <h4 class="book-title">1984</h4>
            <p class="book-author">Джордж Орвелл</p>
            <p class="book-price">220 грн</p>
        </div>

        <div class="third-section-book">
            <img src="https://upload.wikimedia.org/wikipedia/en/6/6b/The_Chronicles_of_Narnia_1st_ed_cover.jpg"
                 alt="Хроніки Нарнії" class="book-img">
            <h4 class="book-title">Хроніки Нарнії</h4>
            <p class="book-author">К.С. Льюїс</p>
            <p class="book-price">300 грн</p>
        </div>

    </div>
</section>

<!-- ПІДВАЛ -->
<footer class="footer">
    <h3 class="section-title footer-title">Приєднуйтесь до нашої спільноти</h3>

    <p class="footer-text">
        <span class="footer-text-main">Підпишіться</span> на новини, події та рекомендації нашої бібліотеки.
    </p>

    <form class="footer-form">
        <h4 class="form-title">Зворотній зв'язок</h4>
        <input class="form-input" type="text" placeholder="Ваше ім’я">
        <input class="form-input" type="email" placeholder="Ваш Email">
        <button class="footer-button" type="button">Відправити</button>
    </form>
</footer>

</body>
</html>
