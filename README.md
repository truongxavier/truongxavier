<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Profil GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .showcase {
            min-height: 400px;
            background: url('showcase.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Mon Profil GitHub</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#projects">Projets</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>Bienvenue sur mon profil GitHub</h1>
            <p>Découvrez mes projets et collaborations.</p>
        </div>
    </section>
    <section class="content">
        <div class="container">
            <h2 id="about">À propos de moi</h2>
            <p>Je suis un développeur passionné par la technologie et l'innovation. J'aime travailler sur des projets open-source et collaborer avec d'autres développeurs.</p>
            <h2 id="projects">Mes Projets</h2>
            <p>Voici quelques-uns de mes projets récents :</p>
            <ul>
                <li>Projet 1</li>
                <li>Projet 2</li>
                <li>Projet 3</li>
            </ul>
            <h2 id="contact">Contact</h2>
            <p>Vous pouvez me contacter via <a href="mailto:monemail@example.com">monemail@example.com</a>.</p>
        </div>
    </section>
</body>
</html>
