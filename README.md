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
                <!-- About Me Section -->
                <div id="about">
                    <h1 style="font-size:25px; text-align:center;"> About Me </h1>
                        <p> Hello, I'm an aspiring games programmer, currently in 4th year studying Computer Game Applications Development at Abertay University! </p>
                        <br>
                        <p> Throughout my course, I have been exposed to many different forms of programming and have been very eager to understand and learn each variant of it. This involves things like AI, physics, graphics or more 
                        generalised object-oriented programming, as you will see across my projects here. </p>
                        <p> I have experience in both C++ and C#, using engines such as Unity and Unreal, or working within SFML and Monogame to design and develop projects. I am also learning Godot to work on an idle game in my free time! </p>
                </div>

                <!-- The Klein Event Section -->
                <div id="thekleinevent">
                    <h1 style="font-size:25px; text-align:center;"> The Klein Event </h1>
                    
                    <div class="tkeLayout">
                        <div class="tkeText">
                            <br>
                            <p> I worked as part of a team called Epoch Productions as one of two programmers to develop 'The Klein Event' - a puzzle horror game set within a time loop upon a spaceship. This was a university project, with the team consisting of 7 students from Abertay, where we had to design and develop our game from scratch over the course of ~4 months. </p>
                            <br>
                            <p> This experience was extremely crucial for showing how my individual skills would translate into a group project - learning how to take ideas from other disciplines and maintaining their vision while producing playable mechanics/features. This made it a perfect chance to develop
                            teamworking and communication skills across the different pipelines of creating a game, connecting all the features I had made with the other programmer and ensuring everything worked as intended. </p>
                            <br>
                            <p> During this project, I also learned how to use industry standard software such as Perforce and Jira within the team environment, essentially simulating what a small studio could be like, consistently updating the team on milestones, where some ends needed refined or trimmed, and ensuring we would meet the deadlines 
                            coming up. </p>
                            <br>
                            <p> Through various play sessions, we iterated different features, adding polish based on feedback, and with industry mentors providing insights, we were able to successfully develop and publish The Klein Event to itch.io, which you can view by clicking the embed below! </p>
                        </div>

                        <div class="tkeMedia">
                            <iframe width="320" height="180" src="https://www.youtube.com/embed/wjItvIRsh_c" title="The Klein Event Trailer" frameborder="0" allowfullscreen> </iframe>
                            <img src="" alt="">
                            <img src="" alt="">
                        </div>
                    </div>

                    <div class="tkeItchLink">
                        <iframe frameborder="0" src="https://itch.io/embed/3343460" width="552" height="167">
                            <a href="https://epochproductions.itch.io/the-klein-event">The Klein Event by EpochProductions</a>
                        </iframe>
                    </div>
                </div>

                <!-- Adventure Game Section -->
                <div id="adventuregame">
                    <h1 style="font-size:25px; text-align:center;"> Adventure Game </h1>
                    <p> This is a mini text-based adventure game which focuses on object-oriented programming to quickly and efficiently implement new features. </p>
                </div>

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
