<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Новостной сайт</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Новости сегодня</h1>
            <nav>
                <a href="index.html">Главная</a>
                <a href="categories.html">Категории</a>
                <a href="about.html">О сайте</a>
            </nav>
        </div>
    </header>
    <main>
        <section class="news">
            <article>
                <h2>Глобальные изменения климата</h2>
                <p>Ученые сообщают о новых тревожных данных...</p>
                <a href="#">Читать далее</a>
            </article>
            <article>
                <h2>Экономика в 2024 году</h2>
                <p>Прогнозы аналитиков: чего ожидать в следующем году.</p>
                <a href="#">Читать далее</a>
            </article>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Новостной сайт</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Категории новостей</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Новости сегодня</h1>
            <nav>
                <a href="index.html">Главная</a>
                <a href="categories.html">Категории</a>
                <a href="about.html">О сайте</a>
            </nav>
        </div>
    </header>
    <main>
        <section class="categories">
            <h2>Категории</h2>
            <ul>
                <li><a href="#">Политика</a></li>
                <li><a href="#">Экономика</a></li>
                <li><a href="#">Наука</a></li>
                <li><a href="#">Спорт</a></li>
                <li><a href="#">Технологии</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Новостной сайт</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>О сайте</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Новости сегодня</h1>
            <nav>
                <a href="index.html">Главная</a>
                <a href="categories.html">Категории</a>
                <a href="about.html">О сайте</a>
            </nav>
        </div>
    </header>
    <main>
        <section class="about">
            <h2>О сайте</h2>
            <p>Наш новостной сайт предоставляет свежие новости со всего мира. Мы стремимся быть объективными и предоставлять только проверенную информацию.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Новостной сайт</p>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 15px 0;
}

.container {
    width: 90%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px 0;
}

.news article, .categories, .about {
    width: 90%;
    margin: 20px auto;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
