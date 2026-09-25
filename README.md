<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Иван & Валерия — свадьба</title>

<style>
* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    background: #f7f1e8;
    color: #3d342b;
    font-family: Georgia, "Times New Roman", serif;
}

.container {
    max-width: 760px;
    margin: 0 auto;
}

/* ГЛАВНЫЙ ЭКРАН */

.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 25px;
    background:
        radial-gradient(circle at top, #fffdf9, transparent 55%),
        linear-gradient(180deg, #fbf7f0, #eee2d2);
}

.card {
    width: 100%;
    padding: 60px 25px;
    border: 1px solid #c8a566;
    background: rgba(255,255,255,0.45);
    box-shadow: 0 20px 60px rgba(80,55,25,0.10);
}

.kicker {
    font-family: Arial, sans-serif;
    font-size: 11px;
    letter-spacing: 4px;
    text-transform: uppercase;
    color: #9b7941;
}

.names {
    font-size: 58px;
    font-weight: normal;
    line-height: 1.1;
    margin: 25px 0 15px;
}

.amp {
    color: #b28b4c;
    font-style: italic;
}

.line {
    width: 80px;
    height: 1px;
    background: #b28b4c;
    margin: 25px auto;
}

.date {
    font-size: 25px;
}

.time {
    margin-top: 12px;
    font-family: Arial, sans-serif;
    font-size: 14px;
    letter-spacing: 3px;
}

.city {
    margin-top: 10px;
    font-size: 18px;
    color: #756453;
}

/* СЕКЦИИ */

section {
    padding: 70px 25px;
    text-align: center;
}

.story {
    background: #fffaf3;
}

.title {
    margin: 0 0 25px;
    font-size: 34px;
    font-weight: normal;
}

.text {
    max-width: 580px;
    margin: auto;
    font-size: 18px;
    line-height: 1.8;
}

/* ДЕТАЛИ */

.details {
    max-width: 650px;
    margin: 40px auto 0;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.detail {
    padding: 25px 10px;
    border-top: 1px solid #c8a566;
    border-bottom: 1px solid #c8a566;
    font-size: 17px;
}

.detail b {
    display: block;
    margin-bottom: 10px;
    color: #9b7941;
    font-family: Arial, sans-serif;
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

/* ИСТОРИЯ */

.timeline {
    margin: 45px auto 0;
    max-width: 600px;
}

.timeline-item {
    padding: 20px;
    border-left: 1px solid #c8a566;
    margin-bottom: 25px;
    text-align: left;
}

.timeline-item strong {
    color: #9b7941;
    font-size: 15px;
}

/* RSVP */

.rsvp {
    background: #eee1cf;
}

.button {
    display: inline-block;
    margin-top: 30px;
    padding: 16px 30px;
    border: 1px solid #a27b3e;
    color: #6c512c;
    text-decoration: none;
    font-family: Arial, sans-serif;
    font-size: 13px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

.button:hover {
    background: #fffaf3;
}

/* ФУТЕР */

.footer {
    padding: 40px 20px;
    text-align: center;
    color: #806f5c;
    font-size: 15px;
}

/* ТЕЛЕФОН */

@media (max-width: 600px) {

    .names {
        font-size: 43px;
    }

    .title {
        font-size: 29px;
    }

    .details {
        grid-template-columns: 1fr;
    }

    .card {
        padding: 50px 18px;
    }
}
</style>
</head>

<body>

<div class="container">

    <!-- ГЛАВНЫЙ ЭКРАН -->

    <header class="hero">

        <div class="card">

            <div class="kicker">
                Приглашение на свадьбу
            </div>

            <div class="names">
                Иван <span class="amp">&</span> Валерия
            </div>

            <div class="line"></div>

            <div class="date">
                16 октября 2026
            </div>

            <div class="time">
                НАЧАЛО В 17:00
            </div>

            <div class="city">
                Ставрополь
            </div>

        </div>

    </header>


    <!-- ПРИГЛАШЕНИЕ -->

    <section class="story">

        <h2 class="title">
            Дорогие родные и близкие!
        </h2>

        <p class="text">
            Мы рады сообщить вам, что совсем скоро
            состоится один из самых важных дней
            нашей жизни.
        </p>

        <br>

        <p class="text">
            Мы будем счастливы разделить этот
            особенный день с вами и вместе создать
            воспоминания, которые останутся с нами
            навсегда.
        </p>

    </section>


    <!-- ДАТА -->

    <section>

        <h2 class="title">
            Когда и где
        </h2>

        <div class="details">

            <div class="detail">
                <b>Дата</b>
                16 октября 2026
            </div>

            <div class="detail">
                <b>Время</b>
                17:00
            </div>

            <div class="detail">
                <b>Город</b>
                Ставрополь
            </div>

        </div>

    </section>


    <!-- ИСТОРИЯ -->

    <section class="story">

        <h2 class="title">
            Наша история
        </h2>

        <p class="text">
            Всё самое красивое начинается с маленьких
            моментов. А теперь мы начинаем новую
            главу нашей общей истории.
        </p>

        <div class="timeline">

            <div class="timeline-item">
                <strong>Когда-то</strong><br>
                Две истории, которые однажды должны
                были встретиться.
            </div>

            <div class="timeline-item">
                <strong>Сегодня</strong><br>
                Мы вместе создаём нашу семью.
            </div>

            <div class="timeline-item">
                <strong>16.10.2026</strong><br>
                День, который станет началом новой
                главы нашей жизни.
            </div>

        </div>

    </section>


    <!-- ПОДТВЕРЖДЕНИЕ -->

    <section class="rsvp">

        <h2 class="title">
            Подтвердите присутствие
        </h2>

        <p class="text">
            Будем очень рады видеть вас рядом
            с нами в этот особенный день.
        </p>

        <a
            class="button"
            href="mailto:?subject=Свадьба%20Ивана%20и%20Валерии&body=Здравствуйте!%20Подтверждаю%20своё%20присутствие."
        >
            Подтвердить
        </a>

    </section>


    <!-- ФУТЕР -->

    <div class="footer">

        С любовью,<br>
        <strong>Иван & Валерия</strong>
        ♡

    </div>

</div>

</body>
</html>
