<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/ico" href="./ico/favicon.ico" />
    <title>Презентации</title>

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
    color: #fff;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.subtitle {
    color: #aaa;
    margin-bottom: 40px;
}

.menu {
    list-style: none;
    width: 100%;
    max-width: 1000px;
    padding: 0 20px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
}

.menu a {
    display: block;
    padding: 20px;
    background: rgba(255,255,255,0.08);
    border-radius: 12px;
    color: white;
    text-decoration: none;
    transition: 0.2s;
}

.menu a:hover {
    background: rgba(255,255,255,0.2);
    transform: translateY(-3px);
}

.label {
    font-size: 0.8rem;
    color: #aaa;
    margin-top: 5px;
}

.footer {
    margin-top: 40px;
    font-size: 14px;
    color: #888;
    text-align: center;
}

.footer a {
    color: #38bdf8;
    text-decoration: none;
    margin: 0 5px;
}
</style>
</head>

<body>

<h1>📽️ Дарья Севостьянова</h1>
<p class="subtitle">Мои презентации</p>

<ul class="menu">
    <li>
        <a href="job-search-short/index.html">
            Коротко про поиск работы
            <div class="label">Презентация</div>
        </a>
    </li>

    <li>
        <a href="job-search-2026/index.html">
            Как искать работу в 2026 году: обзор площадок и взаимодействия с ними
            <div class="label">Презентация</div>
        </a>
    </li>
</ul>

<div class="footer">
    📧 <a href="mailto:dasha.sokolova2003@yandex.ru">dasha.sokolova2003@yandex.ru</a> · 
    💬 <a href="https://t.me/dashasokolova2" target="_blank">Telegram</a>
</div>

</body>
</html>
