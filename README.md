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
        <section id="infoWindow">
            <!---->
            <p id="about" display="flex"> Hello, I'm a 4th year student studying Computer Game Applications Development at Abertay University. <br> I am eager to continue my programming journey into the professional world, with a                   strong passion for learning both new languages, or expanding my current knowledge in others. </p>
            <!---->
            <p id="thekleinevent" style="display:none;"> This will be a thorough breakdown of The Klein Event. </p>
            <!---->
            <script>
            function displayAbout() {
                document.getElementById("about").display = "flex";
                document.getElementById("thekleinevent").display = "none";
                }
            function displayTKE() {
                document.getElementById("about").display = "none";
                document.getElementById("thekleinevent").display = "flex";
                }
            </script>
            <!---->
        </section>
        <section id="projectWindow">
              <h1>Projects</h1>
              <br>
              <!-- <a href="https://doctorjaffa.github.io/thekleinevent.html"> -->
              <image onclick="displayTKE()" src="TKEImage.png" style="width:256px;height:256px; cursor:pointer;" title="The Klein Event Project" > </image>
              <!-- </a> -->
              <br>
              <u><p id="projectLink"><a href="https://doctorjaffa.github.io/thekleinevent.html"> The Klein Event </a></p></u>
        </section>
    </div>

</html>
