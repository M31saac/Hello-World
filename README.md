<html>
<head>
<style>
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
h1{
   text-align: center;
}
h2,h3{
background-color: lightblue;
}
h1, h2, h3, h4{  
color: blue;
font-family:"Times New Roman", Times, serif;
}
.p {
font-family: Arial, Helvetica, sans-serif;
}
th {
background-color: #04AA6D;
color: white;
}
</style>
<title> Mi pagina personal </title>
</head>
<h1>Isaac Mojica</h1>
<br>
<center><img src="Cartoonify.png"width="150" height="150" alt="IsaacMojica" align= “center”></center> 
<h2>Biografía</h2>
<p> Nací el 9 de marzo de 1998, soy una persona tranquila aunque emocional, hedonista, cómico y algo sarcástico. </p>
<hr>   
<h2>Favoritos</h2>
<h3>Platos</h3>
<br>
<ul>
<li>Sushi</li>
<li>Carbonara</li>
<li>Pollo con papas</li>
</ul>
<h3>Pasatiempos</h3>
<ol>
<li>Jugar videojuegos</li>
<li>Leer</li>
<li>Powerlifting</li>
</ol>
<h3>Canciones</h3>
<center> <table  border="1">
<tr>
<th>Genero</th>
<th>Nombre</th>
<th>Autor</th>
<th>Audio</th>
</tr>
<tr>
<td>Rap</td>
<td>René</td>
<td>Residente</td>
<td><audio controls>
    <source src="Rene.mp3" type="audio/mpeg">
</audio></td>
</tr>
<tr>
<td>Alternative</td>
<td>Sick Love</td>
<td>Red Hot Chilli Peppers</td>
<td><audio controls><source src="Sick Love.mp3" type="audio/mpeg">
</audio></td>
</tr> 
<tr>
<td>Pop-Rock</td>
<td>Can't take my eyes of you</td>
<td>Frankie Valli</td>
<td><audio controls><source src="Cant Take My Eyes Off You.mp3" type="audio/mpeg">
</audio></td>
</tr>
</table></center>
<h3>Videojuego</h3>
<center> <img src= "valorant.jpg">
<br>
<a href="https://playvalorant.com/en-us/">Valorant</a> </center> 
<h3>Película</h3>
<center><img src= "parasite.jpg" width="250" height="250"> 
<br>
<video width="320" height="240" controls>
  <source src="Parasite.mp4" type="video/mp4">
</video> </center> 
<body>

<h4>Para mayor información contáctanos:</h4>

<div>
  <form action="/action_page.php">
    <label for="fname">Nombre</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Apellido</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">País</label>
    <select id="country" name="country">
      <option value="Panamá">Panamá</option>
      <option value="Colombia">Colombia</option>
      <option value="Venezuela">Venezuela</option>
    </select>
  
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>

