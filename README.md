<!Doctype html>
<html lang="pt.br">

<Style>
div{background-color:#cce; padding:30px}

</style>

<head>
  <meta charset="utf-8">
  <tittle>Site<tittle>
  <script src="src/script.html"></script>
</head>

<body>

  <h1>Tigre, boi ou Jacaré?</h1>

  <p> Qual deles é um <mark>réptil</mark>?</p>

<figure>
 <img src="img/download.jpg" tittle="Tigre" alt="Tigre" width="300" height="250">
 <img src="img/download (1).jpg" tittle="Boi" alt="Boi" width="300" height="250">
 <img src="img/download (2).jpg" tittle="Jacaré" alt="Jacaré" width="300" height="250">

<form action="cadastro.php" method="post">

<fieldset>

 <legend>Marque apenas uma resposta e justifique o porquê</legend>
Animal:<br>
 <input type="radio" name="animal" value="Tigre"> <mark>Tigre<br></mark>
 <input type="radio" name="animal" value="Boi"> <mark>Boi<br></mark>
 <input type="radio" name="animal" value="Jacaré"> <mark>Jacaré<br></mark>
 <br>

<a href="https://www.google.com.br/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=animal+tigre" tabindex="1">Tigre</a>
<a href="https://www.google.com.br/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=Boi" tabindex="2">Boi</a>
<a href="https://www.google.com.br/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=Jacare" tabindex="3">Jacaré</a>
 <br>
 <input type="submit" name="btn-enviar" value="Enviar"><br>

 Justificativa<br>
<textarea name="mensagem" rows="5" cols="20"></textarea><br><br>
<button type="button">Enviar</Button><br>


 </fieldset>


 </form>

<h2>Gabarito</h2>
 <object width="1240" height="1000" data="Répteis.pdf"></object>


</body>


</html>
