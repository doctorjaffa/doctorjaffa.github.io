<html>
    <head>
      <meta charset="utf-8">
      <link rel="stylesheet" href="/stylesheets/main.css">
    </head>
    <div>
        <header>
            <h1>Nathan Harris</h1>
            <h2>Games Programmer/Developer</h2>
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
                <div id="about" style="display:flex;">
                    <p> Hello, I'm a 4th year student studying Computer Game Applications Development at Abertay University. <br> I am eager to continue my programming journey into the professional world, with a strong                                      passion for learning both new languages, or expanding my current knowledge in others. </p>
                </div>
                <!---->
                <div style="display:none;" id="thekleinevent">
                    <p> This will be a thorough breakdown of The Klein Event. </p>
                </div>
                <!---->
                <script>
                    function displayAbout() {
                        document.getElementById("about").style.display = "flex";
                        document.getElementById("thekleinevent").style.display = "none";
                        }
                    function displayTKE() {
                        document.getElementById("about").style.display = "none";
                        document.getElementById("thekleinevent").style.display = "flex";
                        }
                </script>
                <!---->
            </div>
            <div id="projectWindow">
                  <h1>Projects</h1>
                  <br>
                  <!-- <a href="https://doctorjaffa.github.io/thekleinevent.html"> -->
                  <image onclick="displayTKE()" src="TKEImage.png" style="width:256px;height:256px; cursor:pointer;" title="The Klein Event Project" > </image>
                  <!-- </a> -->
                  <br>
                  <!-- <u><p id="projectLink"><a href="https://doctorjaffa.github.io/thekleinevent.html"> The Klein Event </a></p></u> -->
            </div>
        </section>
    </div>

</html>
