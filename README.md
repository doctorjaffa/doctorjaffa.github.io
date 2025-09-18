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
                    <iframe width="420" height="345" src="https://www.youtube.com/watch?v=wjItvIRsh_c"> </iframe>
                    <br>
                    <p> I worked as part of a team called Epoch Productions as one of two programmers to develop 'The Klein Event' - a puzzle horror game set within a time loop upon a spaceship. This was a university project, with the team consisting of 7 students from Abertay, where we had to design and develop our game from scratch over the course of ~4 months. </p>
                    <br>
                    <p> This experience was extremely crucial for showing me how my individual skills would translate into a team project - learning how to take ideas from other disciplines and maintaining their vision while producing an acceptable product. This was a great time to develop
                    teamworking and communication skills across the different pipelines of games development, and at the end of it produce a playable product that I could proudly release. </p>
                    <p> Alongside this, I also learned how to use industry standard software such as Perforce and Jira within the team environment, essentially simulating what a small studio could be like, consistently updating the team on milestones, where some ends needed refined or trimmed, and ensuring we would meet the deadlines 
                    coming up. </p>
                    <p> Through various play sessions, improving mechanics upon given feedback, and with industry mentors providing insights, I was able to successfully develop and publish The Klein Event onto Itch.io, which you can view by clicking the image below! </p>
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
                  <img onclick="displayTKE()" src="/images/thumbnails/TKEthumbnail.png" title="The Klein Event Project">
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
