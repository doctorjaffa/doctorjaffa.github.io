<html>
    <head>
      <meta charset="utf-8">
      <link rel="stylesheet" href="/stylesheets/main.css">
    </head>
    <body>
        <header>
            <h1>Nathan Harris</h1>
            <h1 style="font-size:20px;">Games Programmer/Developer</h1>
            <!--
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Projects</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            -->
        </header>
        <section id="content">
            <div id="infoWindow">
                <!---->
                <div id="about">
                    <h1 style="font-size:25px; text-align:center;"> About Me </h1>
                    <br>
                    <p> Hello, I'm an aspiring games programmer, currently in 4th year studying Computer Game Applications Development at Abertay University! </p>
                    <br>
                    <p> Throughout my course, I have been exposed to many different forms of programming and have been very eager to understand and learn each variant of it. This involves things like AI, physics, graphics or more 
                    generalised object-oriented programming, as you will see across my projects here. </p>
                    <p> I have experience in both C++ and C#, using engines such as Unity and Unreal, or working within SFML and Monogame to design and develop projects. I am also learning Godot to work on an idle game in my free time! </p>
                </div>
                <!---->
                <div id="thekleinevent">
                    <h1 style="font-size:25px; text-align:center;"> The Klein Event </h1>
                    <p> The Klein Event is a puzzle horror game set within a time loop on a spaceship, developed by Epoch Productions, a team of 7 Abertay University students across multiple disciplines. I worked as one of two programmers to develop the game, with a primary focus on the monster AI and elements of gameplay. </p>
                    <p> This was a project designed and developed from scratch over the course of roughly 4 months and exposed me to a simulation of how a real studio might work - having constant discussions with other disciplines to ensure features were being implemented as envisioned and balance was kept. Through setting clear sprint goals, receiving feedback from various play sessions and industry mentors, I was able to get a crucial understanding of how my individual programming could pair up with a team of other game developers, maintaining consistency with designs handed to me and cohesion with features made by the other programmer. </p>
                </div>
                <div id="adventuregame">
                    <h1 style="font-size:25px; text-align:center;"> Adventure Game </h1>
                    <p> This is a mini text-based adventure game which focuses on object-oriented programming to quickly and efficiently implement new features. </p>
                </div>
                <!---->
                <script>
                    function displayAbout() {
                        document.getElementById("about").style.display = "block";
                        document.getElementById("thekleinevent").style.display = "none";
                        document.getElementById("adventuregame").style.display = "none";
                        }
                    function displayTKE() {
                        document.getElementById("about").style.display = "none";
                        document.getElementById("thekleinevent").style.display = "block";
                        document.getElementById("adventuregame").style.display = "none";
                        }
                    function displayAG() {
                        document.getElementById("about").style.display = "none";
                        document.getElementById("thekleinevent").style.display = "none";
                        document.getElementById("adventuregame").style.display = "block";
                        }
                </script>
                <!---->
            </div>
            <div id="aboutButton" onclick="displayAbout()">
                About Me
            </div>
            <div id="projectWindow">
                  <h1>Projects</h1>
                  <br>
                  <!-- <a href="https://doctorjaffa.github.io/thekleinevent.html"> -->
                  <img onclick="displayTKE()" src="/images/thumbnails/TKEImage.png" title="The Klein Event Project">
                  <img onclick="displayAG()" src="/images/thumbnails/AGImage.png" title="Adventure Game Project">
                  <!-- </a> -->
                  <br>
                  <!-- <u><p id="projectLink"><a href="https://doctorjaffa.github.io/thekleinevent.html"> The Klein Event </a></p></u> -->
            </div>
        </section>
        <footer>
            <a href="https://github.com/doctorjaffa" target="_blank">
                <img src="/images/footer/github-mark-white.png" alt="Github">
            </a>
            <a href="https://bsky.app/profile/doctorjaffa.bsky.social" target="_blank">
                <img src="/images/footer/Bluesky_Logo.png" alt="Bluesky">
            </a>
            <a href="https://www.linkedin.com/in/nathan-harris-b0534a218" target="_blank">
                <img src="/images/footer/InBug-White.png" alt="LinkedIn">
            </a>
            <a href="mailto:nathanharris1502@gmail.com" target="_blank">
                <img src="/images/footer/gmail-logo.png" alt="Gmail">
            </a>
        </footer>
    </body>
</html>
