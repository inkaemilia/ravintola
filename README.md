# ravintola
 <!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Ravintola</title>
<style>
body {
  background-image: url("lappiruoka_opacity50.jpg");
  font-family: Verdana,sans-serif;
  font-size: 0.9em;
}

header {
  border-radius: 10px;
  padding: 10px;
  text-align: center;
  text-shadow: 2px 2px 5px black;
  color: white;
  background-color: rgba(111, 101, 70, 0.6);
}

footer {
  width: 100%
  border-radius: 5px;
  padding: 10px;
  color: white;
  background-color: rgba(111, 101, 70, 0.6);
  position: relative;
  bottom: -50px;
}

article {
  border-radius: 20px;
  margin: 10px;
  padding: 10px;
  background-color: rgba(111, 65, 70, 0.5);
  width: 90%;
  height: 85%;
  position: relative;
  left: 10px;
  top: 10px;
}

.article2 {
  border-radius: 20px;
  margin: 10px;
  padding: 10px;
  background-color: rgba(111, 65, 70, 0.5);
  width: 90%;
  height: 30%;
  position: relative;
  left: 10px;
  top: 10px;
}

.article3 {
  border-radius: 20px;
  margin: 10px;
  padding: 10px;
  background-color: rgba(111, 65, 70, 0.5);
  width: 70%;
  height: 45%;
  position: relative;
  left: 10px;
  top: 20px;
}

nav ul {
  display: flex;
  border-radius: 10px;
  padding: 0;
  height: 150px;
  position: absolute;
  left: 1%;
  top: 20%;
}

nav ul li {
  margin: 10px; 
}

/* Column container */
.row {  
  display: flex;
  flex-wrap: wrap;
  width: 500px;
  position: relative;
  left: 6%;
  top: 15%;
}

.row2 {  
  display: flex;
  flex-wrap: wrap;
  width: 500px;
  position: relative;
  left: 6%;
  top: 15%;
}

/* Sidebar/left column */
.side {
  flex: 50%;
  padding: 10px;
  border-radius: 5px;
  margin: 5px;
  background-color: lightgrey;
  position: relative;
  left: 9%;
  top: 15%;
}

/* Main column */
.main {
  flex: 50%;
  padding: 10px;
  border-radius: 5px;
  margin: 5px;
  padding: 10px;
  background-color: lightgrey;
  position: relative;
  left: 9%;
  top: 15%;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 100px;
  background-color: #f1f1f1;
}

li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: rgba(111, 65, 70, 0.5);
  color: white;
}

div.polaroid {
  width: 50%;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 1px;
  margin-left: 20px;
}

div.container {
  text-align: center;
  padding: 10px 20px;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media (max-width: 700px) {
  .row {   
    flex-direction: column;
	background-image: url("lappiruoka_opacity50.jpg") display: none;
  }
}

</style>
</head>
<body>

<header>
  <h1>RAVINTOLA LAPINTAIKA</h1>
</header>

<nav>
  <ul style="list-style-type:none">
    <li><a href="file:///C:/Users/gr263728/OneDrive%20-%20Jyv%C3%A4skyl%C3%A4n%20koulutuskuntayhtym%C3%A4%20Gradia/Tiedostot/html/asiakaspalaute.html">Kysely</a></li>
    <li><a href="linkki">Linkki</a></li>
    <li><a href="linkki">Linkki</a></li>
  </ul>
</nav>

<div class="row">
 <div class="side">
	 <h2>Ruokalista</h2>
	 <article>
		<p><b>Maanantai</b></p>
		<p>Juusto-vihanneskeittoa ja kokin sämpylä Paistettua lohta, sinappikastiketta, tilliperunoita ja kasviksia. Marjakiisseliä ja hunajakermavaahtoa.</p>

		<p><b>Tiistai</b></p>
		<p>Kana-fetajustosalaattia ja kokin sämpylä Paistettua punakampelaa, pinaattikastiketta ja perunamuusia. Pannukakkua, mansikkahilloa ja kermavaahtoa.</p>

		<p><b>Keskiviikko</b></p>
		<p>Tomaatti-yrttikeittoa ja kokin sämpylä Kalkkunaleikettä, BBQ-kastiketta, riisiä ja kasviksia. Omenapiirakkaa ja vaniljakastiketta.</p>

		<p><b>Torstai</b></p>
		<p>Rapukeittoa ja kokin sämpylä Poronkäristystä, perunamuusia, puolukkahilloa ja suolakurkkuja. Hedelmäsalaattia ja kinuskikastiketta.</p>

		<p><b>Perjantai</b></p>
		<p>Savulohisalaatti ja kokin sämpylä Naudan paahtopaistia, punaviinikastiketta, kermaperunat ja kasviksia. Suklaamousse.</p>
	 </article>
  </div>
</div>

<div class="row2">
  <div class="main">
	  <h2>Yhteystiedot ja aukioloajat</h2>
	  <div class="article2">
		<p>Ravintola Lapintaika, Ravintolakatu 2, 98765 LAPINMAA</p>
		<p>Puh. (012) 345 6789</p>
		<p><b>Sähköposti:</b><a href="">varaukset@jokuposti.net</a></p>
		<p><b>Aukioloajat:</b> ma - pe, 10:30 - 15:00</p>
	  </div>
	<div class="article3">
	  <div class="polaroid">
		<img src="suklaamousse.jpg" width="100%">
		<div class="container">
		<p>Suklaamousse</p>
		</div>
	  </div>
    </div>
  </div>
</div>

<footer>
  <p>&copy; 2022 Ravintola Lapintaika. All rights reserved.</p>
</footer>

</body>
</html>

