<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Букетленд - Квіти в Україні</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">🌼 Букет</div>
            <nav>
                <ul>
                    <li><a href="#home">Головна</a></li>
                    <li><a href="#catalog">Каталог</a></li>
                    <li><a href="#about">Про нас</a></li>
                    <li><a href="#delivery">Доставка</a></li>
                    <li><a href="#reviews">Відгуки</a></li>
                    <li><a href="#contacts">Контакти</a></li>
                </ul>
            </nav>
            <div class="cart">
                <button class="cart-btn">🛒 Кошик</button>
            </div>
        </div>
    </header>

   <main>
        <!-- Головний банер -->
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Замовляйте найкрасивіші букети</h1>
                <p>Свіжі квіти з доставкою по Україні.</p>
                <button class="cta-btn">Переглянути каталог</button>
            </div>
        </section>
     <!-- Каталог -->
        <section id="catalog" class="catalog">
            <div class="container">
                <h2>Наш асортимент</h2>
                <div class="products">
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStZABO21cn2CD6lt-z4j8v8EJJ66WrcVUn2Bj50a9vqP22epBelA0URytUj-6oIRx6mkw&usqp=CAU" alt="Букет троянд">
                        <h3>Букет троянд</h3>
                        <p>Ціна: 550 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5hkHtdmNfsgUsdGuxx5OuCBoYytAyBkzmY26B4Esp142E--JdaeSfi60PgjHn6z-9b3c&usqp=CAU" alt="Квіти в коробці">
                        <h3>Квіти в коробці</h3>
                        <p>Ціна: 800 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsdSHkeXvRY6rD9t89QZLJTs0HBvf2VpwRNA&s" alt="Весняний букет">
                        <h3>Весняний букет</h3>
                        <p>Ціна: 700 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRpROjqAf7MzMDKY1qAJb1CKzK-AagZuNOX1w&s" alt="Букет на день народження">
                        <h3>Букет на день народження</h3>
                        <p>Ціна: 600 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ7RPbQrmtlKPnerqKrFnqtp7T-aXwz9mTkiw&s" alt="Весільний букет">
                        <h3>Весільний букет</h3>
                        <p>Ціна: 1200 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                    <div class="product">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRY3tiitLfuaeWPCYk9am-aL0U5ZfaQwEIAcQ&s" alt="Квіти на співчуття">
                        <h3>Квіти на співчуття</h3>
                        <p>Ціна: 750 грн</p>
                        <button class="add-to-cart">Додати до кошика</button>
                    </div>
                </div>
            </div>
        </section>
<!-- Про нас -->
        <section id="about" class="about">
            <div class="container">
                <h2>Про нас</h2>
                <p>Ми - ваша квіткова служба з безкоштовною доставкою по Україні. Наша компанія має багаторічний досвід в оформленні букетів та доставці квітів. Ми прагнемо надати вам найкращі послуги, тому ретельно підбираємо лише найсвіжіші квіти.</p>
                <p>Наша команда складається з професіоналів, які люблять свою справу та завжди готові допомогти вам обрати найкращий букет для будь-якої нагоди.</p>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAFwXrz0pRrMZXHhQMszoCbfQD7PVdhbC7QRdVFIFFIXGLvAtLKRBiDDU52hfwZcy-xp0&usqp=CAU" alt="Наша команда">
            </div>
        </section>
<!-- Доставка -->
        <section id="delivery" class="delivery">
            <div class="container">
                <h2>Доставка</h2>
                <p>Доставка по всій Україні за 1-2 дні. Можлива адресна доставка у день замовлення.</p>
                <p>Оплата можлива через інтернет-банкінг або накладений платіж.</p>
                <p>З нами ви можете бути впевненими в свіжості і якості квітів, які ви отримуєте.</p>
            </div>
        </section>
<!-- Відгуки -->
        <section id="reviews" class="reviews">
            <div class="container">
                <h2>Відгуки наших клієнтів</h2>
                <div class="review">
                    <p>"Прекрасний сервіс і якість! Замовляла букет для мами на день народження, вона була в захваті!" - Олена</p>
                </div>
                <div class="review">
                    <p>"Дуже вдячна за швидку доставку та свіжі квіти. Рекомендую!" - Катерина</p>
                </div>
                <div class="review">
                    <p>"Замовляв весільний букет. Все було просто чудово! Дякую!" - Андрій</p>
                </div>
            </div>
        </section>
 <!-- Контакти -->
        <section id="contacts" class="contacts">
            <div class="container">
                <h2>Контакти</h2>
                <p>Телефон: +380 (67) 973-85-45</p>
                <p>Email: info@buket.ua</p>
                <form>
                    <label for="message">Ваше повідомлення:</label>
                    <textarea id="message" rows="4" placeholder="Напишіть нам..."></textarea>
                    <button type="submit">Надіслати</button>
                </form>
            </div>
        </section>
    </main>

  <footer>
        <div class="container">
            <p>&copy; 2024 Букетленд. Всі права захищені.Рахнянської Софії</p>
        </div>
    </footer>
</body>
</html>
