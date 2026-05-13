<html>

<head>
    <title>Mana lapa</title>

    <style>

        body{
            margin:0;
            font-family:Arial;
        }

        header{
            width:100%;
            height:80px;
            border-bottom:1px solid gray;
        }

        .logo{
            float:left;
            margin-left:40px;
            margin-top:20px;
        }

        .menu{
            float:left;
            margin-left:200px;
            margin-top:30px;
        }

        .menu a{
            text-decoration:none;
            color:black;
            margin-right:20px;
        }

        .search{
            float:right;
            margin-right:40px;
            margin-top:25px;
        }

        .hero{
            width:100%;
            height:400px;
            border-bottom:1px solid gray;
        }

        .left{
            width:45%;
            float:left;
            margin-left:50px;
            margin-top:80px;
        }

        .left h1{
            font-size:40px;
        }

        .left p{
            color:gray;
        }

        .btn1{
            background:orange;
            border:none;
            padding:10px;
            margin-top:20px;
        }

        .btn2{
            background:lightblue;
            border:none;
            padding:10px;
        }

        .right{
            width:40%;
            height:250px;
            border:1px solid gray;
            float:right;
            margin-right:50px;
            margin-top:70px;
            text-align:center;
            line-height:250px;
            color:gray;
        }

        .news{
            width:100%;
            height:350px;
            margin-top:30px;
        }

        .card{
            width:30%;
            float:left;
            margin-left:25px;
        }

        .img{
            width:100%;
            height:120px;
            border:1px solid gray;
            text-align:center;
            line-height:120px;
            color:gray;
        }

        .card h3{
            font-size:20px;
        }

        .card a{
            color:black;
        }

        .ad{
            width:100%;
            height:200px;
            background:#dff0d8;
            text-align:center;
            padding-top:60px;
        }

        .ad button{
            padding:10px;
            margin:10px;
        }

        .slider{
            width:100%;
            height:350px;
            text-align:center;
            border-top:1px solid gray;
            border-bottom:1px solid gray;
        }

        .slidebox{
            width:80%;
            height:200px;
            border:1px solid gray;
            margin:auto;
            margin-top:20px;
            line-height:200px;
            color:gray;
        }

        .content{
            padding:50px;
        }

        .table{
            width:100%;
        }

        .table div{
            width:30%;
            border:1px solid gray;
            float:left;
            padding:10px;
            margin:5px;
        }

        footer{
            width:100%;
            background:#ffe0b3;
            padding:30px;
            margin-top:100px;
        }

    </style>

</head>

<body>

<header>

    <div class="logo">
        <img src="img/logo.png" height="40">
    </div>

    <div class="menu">
        <a href="">Sākums</a>
        <a href="">Par mums</a>
        <a href="">Kontakti</a>
    </div>

    <div class="search">
        <input type="text" placeholder="Meklēt">
    </div>

</header>

<div class="hero">

    <div class="left">
        <h1>Galvenais virsraksts</h1>

        <p>
            Šeit ir apraksts par uzņēmumu.
            Mēs piedāvājam dažādus risinājumus.
        </p>

        <button class="btn1">Lasīt vairāk</button>
        <button class="btn2">Pieteikties</button>
    </div>

    <div class="right">
        Fona bilde
    </div>

</div>

<div class="news">

    <div class="card">
        <div class="img">Bilde</div>
        <h3>Ziņu virsraksts</h3>
        <a href="">Lasīt vairāk</a>
    </div>

    <div class="card">
        <div class="img">Bilde</div>
        <h3>Ziņu virsraksts</h3>
        <a href="">Lasīt vairāk</a>
    </div>

    <div class="card">
        <div class="img">Bilde</div>
        <h3>Ziņu virsraksts</h3>
        <a href="">Lasīt vairāk</a>
    </div>

</div>

<div class="ad">

    <h2>Reklāma</h2>

    <button>Pirkt</button>
    <button>Izmēģināt</button>

</div>

<div class="slider">

    <h2>Bilde pa visu</h2>

    <div class="slidebox">
        Slīdrāde
    </div>

    <p>● ○ ○</p>

</div>

<div class="content">

    <h2>Heading</h2>

    <p>
        Šeit var būt teksts par projektu vai uzņēmumu.
    </p>

    <ul>
        <li>Pirmais</li>
        <li>Otrais</li>
        <li>Trešais</li>
    </ul>

    <div class="table">

        <div>Value 1</div>
        <div>Value 2</div>
        <div>Value 3</div>

        <div>Value 4</div>
        <div>Value 5</div>
        <div>Value 6</div>

    </div>

</div>

<footer>

    <img src="img/logo.png" height="40">

    <br><br>

    Kontakti <br>
    info@piemers.lv <br>
    +37120000000

    <br><br>

    Autors: Jānis

</footer>

</body>

</html>
