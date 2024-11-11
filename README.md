# 2.Ariketa
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>ADITZAK INDIKATIBOAK</title>
    <style>     
        title { font-family: Arial, sans-serif; color: aqua; background-color:aliceblue}
        body { font-family: Arial, sans-serif; color: rgb(12, 90, 90); background-color: rgb(199, 221, 241);}
        p {text-align: justify; color: #0f7c79;}
        nav a { font-weight:bold; color: #0f7c79;}
        nav {background-color: lightblue;}
        .txikia {
            width: 325px;
            cursor: pointer;
        }

        .handia {
            width: 375px;
        }
       
        .mover {
            font-size: 24px;
            white-space: nowrap;  /* Evita que el texto se divida en varias líneas */
            position: relative;
            animation: moverDerechaIzquierda 5s linear forwards; /* 'forwards' mantiene la posición final */
        }

        /* Definir la animación */
        @keyframes moverDerechaIzquierda {
            0% {
                left: 100%;  /* Comienza a la derecha fuera de la pantalla */
            }
            100% {
                left: 0%; /* Termina en la posición inicial (a la izquierda) */
            }
        }
    </style>
    
</head>
<body>
    <title>NOR-Nork eta NOR NORI</title>
    <nav>
        <a href="Lehena.html">NOR-NORK</a>
        <a href="Bigarrena.html">NOR-NORI</a>
        <a href="Hirugarrena.html">Adibideak</a>
    </nav>
<hr> 
    <h1>Sarrera</h1>
        <p>Argi dago, euskara hizkuntz zaharrenetarikoa dela Europa  zehar. Askok badakite hitz egiten, nahiz ulertzen. Hala ere, besteentzat, bereziki <i>kanpotarrentzat</i>, atzerritzarrentzat, zaila iruditzen zaie ikastea. Ez baita haien ama hizkuntza, baina berdin-berdin, komunikatzeko beharrik ere ez dute, ondorioz, ez dute (gehienak) esfortzu handirik hizkuntza hau ikasteko. Alabaina, euskaldunek ongi idazteko ere zailtasunak edukitzen dituzte, zoritxarrez, aditzak konplexuak eta anitzak baitira.</p>
        <p>Hortaz, teoria handirik ez izan arren, hemen lehenengo bi aditz taula nagusi, paregabeak ikasterako orduan, noski!</p>
        <p>Hauek dira azalduko ditudan taulak:
        </p>
        <ul class="mover">
            <li type="square">Nor-Nork</li>
            <li type="square">Nor-Nori</li>
            <li type="circle"><i>Adibideak</i></li>
        </ul>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Flag_of_the_Basque_Country.svg/1280px-Flag_of_the_Basque_Country.svg.png" id= Ikurrina alt="txikia" onclick="handitu(this)" class="txikia">
        <script>
            function handitu (Ikurrina){
            if (Ikurrina.classList.contains("txikia")) {
                Ikurrina.classList.remove("txikia");
                Ikurrina.classList.add("handia");
            } else {
                Ikurrina.classList.remove("handia");
                Ikurrina.classList.add("txikia");
            }
        }
        </script>
        <br>
        <br>
        <audio src="./Huntza.mp3" controls autoplay loop></audio>

    </body>
</html>
