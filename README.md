<html lang="lv">

<head>
    <meta charset="UTF-8">
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

        .menu a:hover{
            color:orange;
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
            cursor:pointer;
        }

        .btn2{
            background:lightblue;
            border:none;
            padding:10px;
            cursor:pointer;
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
            transition:0.3s;
        }

        .card:hover{
            transform:scale(1.05);
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
            cursor:pointer;
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

        .slidebox img{
            margin-top:10px;
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
        <img src="https://i.pinimg.com/736x/ff/7c/b8/ff7cb81628e19fd9490d94396554f01a.jpg" height="40">
    </div>

    <div class="menu">
        <a href="">Sākums</a>
        <a href="">Par mums</a>
        <a href="">Kontakti</a>
    </div>

    <div class="search">
        <input type="text" id="searchInput" placeholder="Meklēt">
        <button onclick="meklet()">Meklēt</button>
    </div>

</header>

<div class="hero">

    <div class="left">
        <h1 id="mainTitle">Pērc BMW</h1>

        <p>
           Ir jauni modeļi un krāsas. Ja ir kādas velmes piesakaties un pasūtiet.
        </p>

        <button class="btn1" onclick="showMessage()">Lasīt vairāk</button>
        <button class="btn2" onclick="changeTitle()">Pieteikties</button>
    </div>

    <div class="right">
        <img src="https://i.pinimg.com/1200x/7f/31/bf/7f31bf3288cc6a7e6012b600db867b31.jpg" height="200">
    </div>

</div>

<div class="news">

    <div class="card">
       <img src="https://i.pinimg.com/736x/b9/84/06/b984064a0de68eaf5df3a1a20724c08f.jpg" height="200">
        <h3>BMW E36</h3>
        <a href="">Lasīt vairāk</a>
    </div>

    <div class="card">
        <img src="https://i.pinimg.com/736x/42/f0/aa/42f0aa5410300853c7a2d4cb702bc553.jpg" height="200">
        <h3>BMW M3</h3>
        <a href="">Lasīt vairāk</a>
    </div>

    <div class="card">
       <img src="https://i.pinimg.com/1200x/ba/13/f2/ba13f21e2c007ac4cfe9dd3cf3e94d44.jpg" height="200">
        <h3>BMW 740i</h3>
        <a href="">Lasīt vairāk</a>
    </div>

</div>

<div class="ad">

    <h2>Reklāma</h2>

    <button onclick="buyNow()">Pirkt</button>
    <button onclick="tryNow()">Izmēģināt</button>

</div>

<div class="slider">

    <div class="slidebox">
       <img id="sliderImage"
       src="https://i.pinimg.com/736x/37/cd/aa/37cdaa51640ed391e2a64a73d259880c.jpg"
       height="200">
    </div>

    <br>

    <button onclick="previousSlide()">◀</button>
    <button onclick="nextSlide()">▶</button>

</div>

<div class="content">

    <h2>Cenas</h2>

    <p>
        Liela dažādība mašīnu cenās
    </p>

    <ul>
        <li>Pirmais</li>
        <li>BMW M3</li>
        <li>BMW 740i</li>
    </ul>

    <div class="table">

        <div>BMW E36 - 125k</div>
        <div>BMW M3 - 200k</div>
        <div>BMW 740i - 250k</div>

        <div>Custom - 175k</div>
        <div>Custom - 250k</div>
        <div>Custom - 300k</div>

    </div>

</div>

<footer>

    <img src="https://i.pinimg.com/736x/ff/7c/b8/ff7cb81628e19fd9490d94396554f01a.jpg" height="40">

    <br><br>

    Kontakti <br>
    bmwnotreal@gmail.com <br>
    +37128195023

    <br><br>

    Autors: Kristofers Platais

</footer>

<script>

    function showMessage(){
        alert("BMW piedāvā jaunākos modeļus un īpašas cenas!");
    }

    function changeTitle(){
        document.getElementById("mainTitle").innerHTML = "Paldies par pieteikšanos!";
    }

    function meklet(){
        let value = document.getElementById("searchInput").value;
        alert("Tu meklēji: " + value);
    }

    function buyNow(){
        alert("Pirkums veiksmīgi sākts!");
    }

    function tryNow(){
        alert("Testa brauciens rezervēts!");
    }

    let images = [
        "https://i.pinimg.com/736x/37/cd/aa/37cdaa51640ed391e2a64a73d259880c.jpg",
        "https://i.pinimg.com/736x/b9/84/06/b984064a0de68eaf5df3a1a20724c08f.jpg",
        "https://i.pinimg.com/736x/42/f0/aa/42f0aa5410300853c7a2d4cb702bc553.jpg"
    ];

    let current = 0;

    function nextSlide(){
        current++;

        if(current >= images.length){
            current = 0;
        }

        document.getElementById("sliderImage").src = images[current];
    }

    function previousSlide(){
        current--;

        if(current < 0){
            current = images.length - 1;
        }

        document.getElementById("sliderImage").src = images[current];
    }

</script>

</body>

</html>
