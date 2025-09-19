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
                    <div class="infoLayout">
                        <div class="infoText">
                            <h1> About Me </h1>
                                <p> Hello, I'm an aspiring games programmer, currently in 4th year studying Computer Game Applications Development at Abertay University! </p>
                                <br>
                                <p> Throughout my course, I have been exposed to many different forms of programming and have been very eager to understand and learn each variant of it. This involves things like AI, physics, graphics or more 
                                generalised object-oriented programming, as you will see across my projects here. </p>
                                <p> I have experience in both C++ and C#, using engines such as Unity and Unreal, or working within SFML and Monogame to design and develop projects. I am also learning Godot to work on an idle game in my free time! </p>
                        </div>

                        <div class="infoMedia">
                            <img src="" alt="">
                        </div>
                    </div>
                </div>

                <!-- The Klein Event Section -->
                <div id="thekleinevent"> 
                    <div class="infoLayout">
                        <div class="infoText">
                            <h1> The Klein Event </h1>
                            <br>
                            <p> I worked as part of a team called Epoch Productions as one of two programmers to develop 'The Klein Event' - a puzzle horror game set within a time loop upon a spaceship. This was a university project, with the team consisting of 7 students from Abertay, where we had to design and develop our game from scratch over the course of ~4 months. </p>
                            <br>
                            <p> This experience was extremely crucial for showing how my individual skills would translate into a group project - learning how to take ideas from other disciplines and maintaining their vision while producing playable mechanics/features. This made it a perfect chance to develop
                            teamworking and communication skills across the different pipelines of creating a game, connecting all the features I had made with the other programmer and ensuring everything worked as intended. </p>
                            <br>
                            <p> During this project, we used an industry-standard pipeline, with Perforce for version control and Jira for task management. This helped us keep on track of milestones, prioritising tasks and trimming others to ensure we would meet those deadlines, and building iterations of the project across numerous 
                            sprints, essentially simulating the workflow of a small games studio. I became very comfortable using these software to manage my own tasks and ensure I was keeping up with the pace set by others, as well as understanding where other disciplines were 
                            at and making sure we were all working in tandem to produce the released game. </p>
                            <br> <br>
                            <p> Through various playtest sessions, I refined systems and features based on feedback, such as constantly fine-tuning the monster AI balance so people felt its presence without it being unfair. With industry mentors providing additional insights, we were able to 
                            successfully develop and publish The Klein Event to itch.io, my first full group experience of making a game start to finish, which you can view by clicking below! </p>

                            <div class="tkeItchLink">
                                <iframe frameborder="0" src="https://itch.io/embed/3343460" width="552" height="167">
                                    <a href="https://epochproductions.itch.io/the-klein-event">The Klein Event by EpochProductions</a>
                                </iframe>
                            </div>
                        </div>

                        <div class="infoMedia">
                            <iframe src="https://www.youtube.com/embed/wjItvIRsh_c" title="The Klein Event Trailer" frameborder="0" allowfullscreen height="250px"> </iframe>
                            <img src="/images/media/tke/tkemedia1.gif" alt="Monster Running">
                            <img src="/images/media/tke/tkemedia2.png" alt="Broken Escape Pod">
                            <img src="/images/media/tke/tkemedia3.png" alt="Kitchen Environment">
                        </div>
                    </div>
                </div>

                <!-- Adventure Game Section -->
                <div id="adventuregame">
                    <div class="infoLayout">
                        <div class="infoText">
                            <h1> Adventure Game </h1>
                            <p> This project is an older text-based adventure game, created solely using C++ and its i/o stream, to deliver a short interactive experience to the player. By limiting it to just text, this allowed me to focus purely on the foundations of programming concepts without needing 
                            fancy graphics or built-in systems. </p>

                            <p> This game features branching areas, an inventory system, and simple combat, all designed with object-oriented programming principles to help me understand and execute them in future, bigger scope projects.
                            Everything in the project derives from a simple 'Thing' base class, allowing me to rapidly expand the game's scope by adding new child classes without having to update existing systems to ensure it all works together. This approach
                            to my project showed me the very strong benefits of modular design and programming.</p>

                            <p> The biggest goal for this project was foresight - designing it in a way that allows new content to be added into the game extremely fast, allowing my systems to scale up in scope much more rapidly than other programming styles.
                            While this is a much simpler project and smaller in scope, it gave me the core foundations in building modular code, without relying on anything but my own programming design and implementations, that I will take forward into any future 
                            project I work on, both personally or professionally. </p>
                        </div>

                        <div class="infoMedia">
                            <img src="/images/media/ag/agmedia1.png" alt"Looking at Area">
                            <img src="/images/media/ag/agmedia2.png" alt="Combat Example">
                            <img src="/images/media/ag/agmedia3.png" alt="Analysing Enemy">
                        </div>
                    </div>
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
