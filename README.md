<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>galeria de fotos</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="icon" type="image/x-icon" href="logo.png">
  </head>
  <body>
    <ul class="menu">
      <div class="menuToggle"><ion-icon name="add-outline"></ion-icon></div>
      <li style="--i: 0; --clr: #ff2972">
        <a href="foto1.html"><ion-icon name="home-outline"></ion-icon></a>
      </li>
      <li style="--i: 1; --clr: #fee800">
        <a href="foto2.html"><ion-icon name="settings-outline"></ion-icon></a>
      </li>
      <li style="--i: 2; --clr: #04fc43">
        <a href="foto3.html"><ion-icon name="mail-outline"></ion-icon></a>
      </li>
      <li style="--i: 3; --clr: #fe00f1">
        <a href="foto4.html"><ion-icon name="key-outline"></ion-icon></a>
      </li>
      <li style="--i: 4; --clr: #00b0fe">
        <a href="foto5.html"><ion-icon name="camera-outline"></ion-icon></a>
      </li>
    </ul>
    <script
      type="module"
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"
    ></script>
    <script
      nomodule
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"
    ></script>
    <script>
      let menuToggle = document.querySelector(".menuToggle");
      let menu = document.querySelector(".menu");
      menuToggle.onclick = function () {
        menu.classList.toggle("active");
      };
    </script>
  </body>
</html>
