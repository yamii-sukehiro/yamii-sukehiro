### Hi there 👋
<head>

  <title>yami_nix</title>

</head>

<body>

  <h1>Hiiiiiiiiii</h1>

  <p>Das ist nur ein test.</p>

  <form action="upload.php" method="post" enctype="multipart/form-data">

    <input type="file" name="bild">

    <input type="submit" value="Hochladen">

  </form>

</body>

</html>

<?php

if ($_FILES["bild"]["error"] == UPLOAD_ERR_OK) {

  $ziel = "bilder/" . basename($_FILES["bild"]["name"]);

  move_uploaded_file($_FILES["bild"]["tmp_name"], $ziel);

  echo "Das Bild wurde erfolgreich hochgeladen.";

} else {

  echo "Es ist ein Fehler beim Hochladen des Bildes aufgetreten.";

}

?>

</html>

<img src="anime-bild.jpg" alt="Ein Anime-Bild" width="500" height="300">

<a href="neue-website.html" target="_blank">

  <img src="anime-bild.jpg" alt="Ein Anime-Bild" width="500" height="300">

</a>

<header>

   <link href="https://fonts.googleapis.com/css2?family=Lato&display=swap" rel="stylesheet">

</header>

<h1>hergestelt von Ramin</h1>

<p>Hover us and enjoy the satisfying neumorphic animation designs!</p>

<div class="frame">

  <button class="custom-btn btn-1">Marin</button>

  <button class="custom-btn btn-2">yami</button>

  <button class="custom-btn btn-3">akari</button>

  <button class="custom-btn btn-4">Zorro</button>

body { background-image: url("https://artfiles.alphacoders.com/740/74060.jpg") }.

<!DOCTYPE html>

<html>

<head>

	<title>Meine Webseite</title>

</head>

<body>

	<h1>Bilder hochladen</h1>

	<form action="upload.php" method="post" enctype="multipart/form-data">

		<input type="file" name="bild">

		<input type="submit" value="Hochladen">

	</form>

</body>

</html>

<!DOCTYPE html>

<html>

  <head>

    <title>My Page</title>

    <style>

      body {

        background: #e0e5ec;

      }

      h1 {

        position: relative;

        text-align: center;

        color: #353535;

        font-size: 50px;

        font-family: "Cormorant Garamond", serif;

      }

      p {

        font-family: 'Lato', sans-serif;

        font-weight: 300;

        text-align: center;

        font-size: 18px;

        color: #676767;

      }

      .frame {

        width: 90%;

        margin: 40px auto;

        text-align: center;

      }

      button {

        margin: 20px;

      }

      .custom-btn {

        width: 130px;

        height: 40px;

        color: #fff;

        border-radius: 5px;

        padding: 10px 25px;

        font-family: 'Lato', sans-serif;

        font-weight: 500;

        background: transparent;

        cursor: pointer;

        transition: all 0.3s ease;

        position: relative;

        display: inline-block;

        box-shadow: inset 2px 2px 2px 0px rgba(255,255,255,.5), 7px 7px 20px 0px rgba(0,0,0,.1), 4px 4px 5px 0px rgba(0,0,0,.1);

        outline: none;

      }

      /* 1 */

      .btn-1 {

        background: rgb(6,14,131);

        background: linear-gradient(0deg, rgba(6,14,131,1) 0%, rgba(12,25,180,1) 100%);

        border: none;

      }

      .btn-1:hover {

        background: rgb(0,3,255);

        background: linear-gradient(0deg, rgba(0,3,255,1) 0%, rgba(2,126,251,1) 100%);

      }

      .btn-2 {

        background: rgb(6,14,131);

        background: linear-gradient(0deg, rgba(6,14,131,1) 0%, rgba(12,25,180,1) 100%);

        border: none;

      }

      .btn-2:hover {

        background: rgb(0,3,255);

        background: linear-gradient(0deg, rgba(0,3,255,1) 0%, rgba(2,126,251,1) 100%);

      }

      .btn-3 {

        background: rgb(6,14,131);

        background: linear-gradient(0deg, rgba(6,14,131,1) 0%, rgba(12,25,180,1) 100%);

        border: none;

      }

      .btn-3:hover {

        background: rgb(0,3,255);

        background: linear-gradient(0deg, rgba(0,3,255,1) 0%, rgba(2,126,251,1) 100%);

      }

      .btn-4 {

        background: rgb(6,14,131);

        background: linear-gradient(0deg, rgba(6,14,131,1) 0%, rgba(12,25,180,1) 100%);

        border: none;

      }

      .btn-4:hover {

        background: rgb(0,3,255);

        background: linear-gradient(0deg, rgba(0,3,255,1) 0%, rgba(2,126,251,1) 100%);

      }

    </style>

  </head>

  <body>

    <h1>Welcome to My Page</h1>

    <p>This is a paragraph of text.</p>

    <div class="frame">

      <button class="custom-btn btn-1">Button 1</button>

      <button class="custom-btn btn-2">Button 2</button>

      <button class="custom-btn btn-3">Button 3</button>

      <button class="custom-btn btn-4">Button 4</button>

    </div>

  </body>

</html>

<!DOCTYPE html>

<html>

<head>

  <title>Download Image on Button Click</title>

</head>

<body>

  <img id="myImage" src="https://artfiles.alphacoders.com/798/thumb-800-79883.webp" alt="Image to Download">

  <button onclick="downloadImage()">Download Image</button>

  <script>

    function downloadImage() {

      var link = document.createElement('a');

      link.download = 'image.jpg';

      link.href = document.getElementById('myImage').src;

      link.click();

    }

  </script>

</body>

</html>

<script>

function scrollNav() {

  $('a').click(function(){

    $(".active").removeClass("active");

    $(this).addClass("activ e");

    $('html, body').stop().animate({

        scrollTop: $($(this).attr('href')).offset().top - 160

    }, 300);

    return false;

  });

}

scrollNav();

</script>






