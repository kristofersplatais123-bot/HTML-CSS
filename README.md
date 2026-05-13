<!DOCTYPE html>
<html lang="lv">
<head>
<meta charset="UTF-8">
<title>Mājaslapa</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #fff;
}

/* ===== HEADER ===== */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 60px;
    border-bottom: 1px solid #ddd;
}

nav a {
    margin: 0 12px;
    text-decoration: none;
    color: #000;
    font-size: 14px;
}

.search {
    display: flex;
    align-items: center;
    gap: 5px;
    border: 1px solid #ccc;
    padding: 3px 8px;
    border-radius: 4px;
}

.search input {
    border: none;
    outline: none;
}

/* ===== HERO ===== */
.hero {
    display: flex;
    justify-content: space-between;
    padding: 60px;
    border-bottom: 1px solid #ddd;
}

.hero-text {
    max-width: 50%;
}

.hero h1 {
    font-size: 32px;
    margin-bottom: 15px;
}

.hero p {
    color: #444;
    margin-bottom: 20px;
    line-height: 1.5;
}

.btn {
    padding: 10px 16px;
    border: none;
    cursor: pointer;
    margin-right: 10px;
    border-radius: 5px;
}

.btn-yellow {
    background: #f4b400;
}

.btn-blue {
    background: #cfe3ff;
}

/* fona bilde */
.hero-image {
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #999;
    font-size: 14px;
}

/* ===== NEWS ===== */
.news {
    display: flex;
    justify-content: space-between;
    padding: 50px 60px;
    gap: 20px;
    border-bottom: 1px solid #ddd;
}

.card {
    width: 33%;
}

.card-img {
    height: 120px;
    border: 1px solid #ccc;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 10px;
    font-size: 14px;
}

.card h3 {
    font-size: 16px;
    margin-bottom: 8px;
}

.card a {
    font-size: 14px;
    color: #000;
}

/* ===== AD ===== */
.ad {
    background: #cfe8cf;
    text-align: center;
    padding: 60px;
}

.ad h2 {
    margin-bottom: 20px;
}

.ad button {
    padding: 10px 20px;
    border: 1px solid #aaa;
    margin: 0 10px;
    cursor: pointer;
}

/* ===== SLIDER ===== */
.slider {
    padding: 60px;
    text-align: center;
    border-top: 1px solid #ddd;
    border-bottom: 1px solid #ddd;
}

.slider-box {
    height: 200px;
    border: 1px solid #ccc;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 20px 0;
}

.dots {
    font-size: 18px;
}

/* ===== CONTENT ===== */
.content {
    padding: 60px;
}

.content h2 {
    margin-bottom: 15px;
}

.content p {
    margin-bottom: 15px;
    color: #444;
    line-height: 1.5;
}

.content ul {
    margin-left: 20px;
    margin-bottom: 20px;
}

.table {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    border: 1px solid #ccc;
    padding: 10px;
}

/* ===== FOOTER ===== */
footer {
    background: #ffe8c2;
    padding: 30px 60px;
}

.footer-top {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
}

.footer-bottom {
    text-align: center;
    border-top: 1px solid #ddd;
    padding-top: 10px;
    font-size: 14px;
}
</style>

</head>

<body>

<header>
    <div><b>LOGO</b></div>

    <nav>
        <a href="#">Sākums</a>
        <a href="#">Par mums</a>
        <a href="#">Kontakti</a>
    </nav>

    <div class="search">
        🔍 <input type="text" placeholder="Meklēt">
    </div>
</header>

<section class="hero">
    <div class="hero-text">
        <h1>Galvenais virsraksts</h1>
        <p>
            Šeit ir vieta aprakstam par uzņēmumu vai projektu.
            Mēs piedāvājam kvalitatīvus risinājumus.
        </p>
        <button class="btn btn-yellow">Lasīt vairāk</button>
        <button class="btn btn-blue">Pieteikties</button>
    </div>

    <div class="hero-image">
        Fona bilde pa visu platumu
    </div>
</section>

<section class="news">
    <div class="card">
        <div class="card-img">Ziņas bilde</div>
        <h3>Kaut kāds virsraksts</h3>
        <a href="#">Lasīt vairāk</a>
    </div>

    <div class="card">
        <div class="card-img">Ziņas bilde</div>
        <h3>Kaut kāds virsraksts</h3>
        <a href="#">Lasīt vairāk</a>
    </div>

    <div class="card">
        <div class="card-img">Ziņas bilde</div>
        <h3>Kaut kāds virsraksts</h3>
        <a href="#">Lasīt vairāk</a>
    </div>
</section>

<section class="ad">
    <h2>Reklāmas virsraksts</h2>
    <button>Pirkt</button>
    <button>Izmēģināt</button>
</section>

<section class="slider">
    <h2>Bilde pa visu</h2>
    <div class="slider-box">Slīdrāde</div>
    <div class="dots">● ○ ○</div>
</section>

<section class="content">
    <h2>Heading</h2>

    <p>Šeit var ievietot aprakstu par piedāvājumu vai projektu.</p>

    <ul>
        <li>Pirmais punkts</li>
        <li>Otrais punkts</li>
        <li>Trešais punkts</li>
    </ul>

    <div class="table">
        <div>Value 1</div><div>Value 2</div><div>Value 3</div>
        <div>Value 4</div><div>Value 5</div><div>Value 6</div>
        <div>Value 7</div><div>Value 8</div><div>Value 9</div>
    </div>
</section>

<footer>
    <div class="footer-top">
        <div>Logo</div>

        <div>
            <b>Kontakti</b><br>
            E-pasts: info@piemers.lv<br>
            Tel: +371 20000000
        </div>

        <div>
            <b>Izvēlne</b><br>
            Sākums<br>
            Par mums<br>
            Kontakti
        </div>
    </div>

    <div class="footer-bottom">
        Autors: Jānis Seržants
    </div>
</footer>

</body>
</html>
