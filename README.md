<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Nathan Harris Portfolio</title>
  <link rel="stylesheet" href="main.css">
</head>
<body>
  <header>
    <h1>Nathan Harris</h1>
    <h2>Games Programmer/Developer</h2>
  </header>

  <section id="content">
    <div id="infoWindow">
      <div id="about">
        <p>
          Hello, I'm a 4th year student studying Computer Game Applications Development at Abertay University. 
          I am eager to continue my programming journey into the professional world, with a strong passion for 
          learning both new languages or expanding my current knowledge in others.
        </p>
      </div>
      <div id="thekleinevent">
        <p>This will be a thorough breakdown of The Klein Event.</p>
      </div>
    </div>
    <div id="projectWindow">
      <h1>Projects</h1>
      <img onclick="displayTKE()" src="TKEImage.png" title="The Klein Event Project">
    </div>
  </section>

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
</body>
</html>
