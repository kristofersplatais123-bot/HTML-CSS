# HTML-CSS
<!DOCTYPE html>
<html lang="lv">
<head>
<meta charset="UTF-8">
<title>Mājaslapa</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    padding: 15px 40px;
    border-bottom: 1px solid #ccc;
}

nav a {
    margin: 0 10px;
    text-decoration: none;
    color: black;
}

/* Hero */
.hero {
    display: flex;
    justify-content: space-between;
    padding: 50px 40px;
    background: #f5f5f5;
}

.hero button {
    margin-right: 10px;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
}

.hero .primary {
    background: orange;
}

.hero .secondary {
    background: lightblue;
}

/* News */
.news {
    display: flex;
    justify-content: space-around;
    padding: 30px;
}

.card {
    width: 30%;
    border: 1px solid #ccc;
    padding: 10px;
}

/* Banner */
.banner {
    background: #cfe8cf;
    text-align: center;
    padding: 60px;
    font-size: 24px;
}

/* Slider */
.slider {
    text-align: center;
    padding: 60px;
    background: #eee;
}

/* Content */
.content {
    padding: 40px;
}

/* Footer */
footer {
    background: #ffe9c6;
    padding: 20px;
    display: flex;
    justify-content: space-between;
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
</header>

<section class="hero">
    <div>
        <h1>Jaunumu un informācijas lapa</h1>
        <p>Šeit var ievietot galveno aprakstu par mājaslapu vai projektu.</p>
        <button class="primary">Lasīt vairāk</button>
        <button class="secondary">Pieteikties</button>
    </div>
    <div>
        <p><b>Fona bilde pa visu platumu</b></p>
    </div>
</section>

<section class="news">
    <div class="card">
        <h3>Sports</h3>
        <p>Jaunākās sporta ziņas un notikumi.</p>
    </div>

    <div class="card">
        <h3>Tehnoloģijas</h3>
        <p>Jaunumi par datoriem, telefoniem un internetu.</p>
    </div>

    <div class="card">
        <h3>Kultūra</h3>
        <p>Notikumi mākslā, mūzikā un kino.</p>
    </div>
</section>

<section class="banner">
    Reklāmas vieta – īpašs piedāvājums!
</section>

<section class="slider">
    <h2>Attēlu galerija</h2>
    <p>⬅️   ● ● ●   ➡️</p>
</section>

<section class="content">
    <h2>Par mūsu projektu</h2>
    <p>
        Šī lapa ir veidota kā mācību projekts, lai parādītu HTML un CSS struktūru.
        Tā satur navigāciju, ziņu blokus, reklāmas sadaļu un galeriju.
    </p>

    <ul>
        <li>Vienkāršs dizains</li>
        <li>Strukturēta lapa</li>
        <li>Responsīvs izkārtojums (pamata līmenī)</li>
    </ul>
</section>

<footer>
    <div><b>LOGO</b></div>

    <div>
        <p>Kontakti:</p>
        <p>epasts: info@piemers.lv</p>
        <p>tālr: +371 20000000</p>
    </div>

    <div>
        <a href="#">Sākums</a><br>
        <a href="#">Par mums</a><br>
        <a href="#">Kontakti</a>
    </div>
</footer>

</body>
</html>
