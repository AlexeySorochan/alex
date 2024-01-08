<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя веб-сторінка</title>
</head>
<body>

    <header>
        <h1>Ласкаво просимо на мою веб-сторінку!</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Головна</a></li>
            <li><a href="#">Про нас</a></li>
            <li><a href="#">Послуги</a></li>
            <li><a href="#">Контакти</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Про нас</h2>
            <p>Тут може бути опис вашої компанії чи проекту.</p>
            <img src="image.jpg" alt="Описовий зображення">
        </section>

        <section>
            <h2>Наші послуги</h2>
            <ul>
                <li>Послуга 1</li>
                <li>Послуга 2</li>
                <li>Послуга 3</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Моя веб-сторінка. Всі права захищені.</p>
    </footer>

    <form>
        <label for="username">Ім'я користувача:</label>
        <input type="text" id="username" name="username" required>

        <label for="password">Пароль:</label>
        <input type="password" id="password" name="password" required>

        <label for="email">Електронна пошта:</label>
        <input type="email" id="email" name="email" required>

        <label for="subscribe">Підписатися на розсилку:</label>
        <input type="checkbox" id="subscribe" name="subscribe">

        <input type="submit" value="Відправити">
    </form>

</body>
</html>
