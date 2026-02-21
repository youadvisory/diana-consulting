# diana-consulting
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Diana Horodko | Мовні консультації</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #ffffff;
    color: #1f1f1f;
    line-height: 1.7;
}

.wrapper {
    max-width: 850px;
    margin: auto;
    padding: 60px 20px;
}

header {
    text-align: center;
    margin-bottom: 60px;
}

h1 {
    font-size: 32px;
    font-weight: 500;
    margin-bottom: 10px;
}

.subtitle {
    font-size: 16px;
    color: #555;
}

.button {
    display: inline-block;
    margin-top: 25px;
    padding: 12px 26px;
    border: 1px solid #1f1f1f;
    text-decoration: none;
    color: #1f1f1f;
    font-size: 14px;
    transition: 0.3s;
}

.button:hover {
    background: #1f1f1f;
    color: #ffffff;
}

section {
    margin-bottom: 55px;
}

h2 {
    font-size: 20px;
    font-weight: 500;
    margin-bottom: 20px;
    border-bottom: 1px solid #e5e5e5;
    padding-bottom: 8px;
}

ul {
    padding-left: 18px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    font-size: 14px;
}

textarea {
    min-height: 120px;
}

footer {
    border-top: 1px solid #e5e5e5;
    padding-top: 25px;
    font-size: 13px;
    color: #666;
}
</style>
</head>

<body>

<div class="wrapper">

<header>
    <h1>Diana Horodko</h1>
    <div class="subtitle">
        Мовні консультації та англійсько-український переклад
    </div>
</header>

<section>
    <h2>Мовні консультації</h2>
    <p>
    Консультаційна підтримка з питань перекладу,
    формулювання офіційних документів та міжнародної комунікації.
    </p>
</section>

<section>
    <h2>Форма запиту</h2>

    <!-- ЗАМІНИ email -->
    <form action="https://formsubmit.co/your_email@gmail.com" method="POST">

        <input type="text" name="name" placeholder="Ваше ім'я" required>
        <input type="email" name="email" placeholder="Ваш Email" required>
        <textarea name="message" placeholder="Опишіть запит або прикріпіть текст для консультації" required></textarea>

        <input type="hidden" name="_captcha" value="false">
        <input type="hidden" name="_next" value="https://google.com">

        <button type="submit" class="button">Надіслати запит</button>

    </form>
</section>

<section>
    <h2>Контакти</h2>
    Телефон: +380936942936<br>
    м. Коломия, Україна
</section>

<footer>
    ФОП Городько Діана Володимирівна<br>
    Єдиний податок, 2 група | Зареєстровано 29.01.2026
</footer>

</div>

</body>
</html>